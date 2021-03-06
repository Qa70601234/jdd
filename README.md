#!/usr/bin/env bash

## 当前脚本清单（以脚本名前缀排序）
##############################  京  东  商  城  ##############################
## 列表格式： | 脚本名 | 活动名 | 备注内容 |

> 青蛙库
> ql repo https://github.com/smiek2221/scripts.git "jd_" "" "ZooFaker_Necklace.js|JDJRValidator_Pure.js|sign_graphics_validate.js"

> Faker集合仓库
> ql repo https://ghproxy.com/https://github.com/shufflewzc/faker2.git "jd_|jx_|getJDCookie" "activity|backUp" "^jd[^_]|USER|ZooFaker_Necklace"

> 混沌的京东京喜系列
> ql repo https://github.com/whyour/hundun.git "quanx" "tokens|caiyun|didi|donate|fold|Env"

> 龙猪猪的京豆雨
> ql repo https://github.com/longzhuzhu/nianyu.git "qx" “main”

> star261
> ql repo https://ghproxy.com/https://github.com/star261/jd.git "scripts" "code"

> Helloword
> ql repo https://ghproxy.com/https://github.com/JDHelloWorld/jd_scripts.git "jd_|jx_|getJDCookie" "activity|backUp" "^jd[^_]|USER"

> LXK0301备份库
> ql repo https://ghproxy.com/https://github.com/chinnkarahoi/jd_scripts.git "jd_|jx_|getJDCookie" "activity|backUp" "^jd[^_]|USER"

> 柠檬代维护集成库
> ql repo https://ghproxy.com/https://github.com/panghu999/jd_scripts.git "jd_|jx_|getJDCookie" "activity|backUp" "^jd[^_]|USER"

> 柠檬京东脚本私库（胖虎库）不定时开
> ql repo https://ghproxy.com/https://github.com/panghu999/panghu.git "jd_"

> Aaron-lv的库
> https://github.com/Aaron-lv/sync/tree/jd_scripts

>cdle的库    
> https://github.com/cdle/jd_study

> smiek2221
> https://github.com/smiek2221/scripts
> scripts_base_url_10=${DownloadJudgment}https://raw.githubusercontent.com/smiek2221/scripts/master/
> my_scripts_list_10="jd_sign_graphics.js jd_joy_steal.js gua_wealth_island.js jd_summer_movement.js jd_summer_movement_help.js"

> jiulan
> https://github.com/jiulan/platypus
> scripts_base_url_11=${DownloadJudgment}https://raw.githubusercontent.com/jiulan/platypus/main/scripts/
> my_scripts_list_11="jd_shop_sign.js jd_joypark_task.js"

> moposmall
> https://github.com/moposmall/Script
> scripts_base_url_7=${DownloadJudgment}https://raw.githubusercontent.com/moposmall/Script/main/Me/
> my_scripts_list_7="jx_mc_coin.js jx_mc_emptycabbage.js"

> curtinlv
> https://github.com/curtinlv/JD-Script
> scripts_base_url_8=${DownloadJudgment}https://raw.githubusercontent.com/curtinlv/JD-Script/main/
> my_scripts_list_8="jd_cashHelp.py jd_jxgc_tuan.py jd_qjd.py"




## 短期或长期活动：
# jd_try.js                    京东试用
# jd_sqdyj.js                  省钱大赢家翻翻乐             （柠檬版）
# jd_sq.js                     省钱大赢家翻翻乐获取邀请码
# jd_wsdlb.js                  柠檬我是大老板农场           （需要种水果）
# jd_SplitRedPacket.js         天降红包                     （默认助力第一个账号）
# jd_ddnc_farmpark.js          东东乐园
# jd_necklace.js               点点券
# jx_cfdtx.js                  京喜财富岛提现
# jx_mc_coin.js                京喜牧场收集金币
# jx_mc_emptycabbage.js        京喜牧场清空白菜
# Andy_sendBeans.js            送豆得豆
# ddo_pk.js                    京享值PK
# long_half_redrain.js         半点红包雨
# long_super_redrain.js        整点红包雨
# star_dreamFactory_tuan.js    京喜工厂开团

## 一次性活动脚本：

##############################  近  期  删  除  的  活  动  脚  本  ##############################
# jd_superBrand.js
# jd_qqtmy.js
# jd_limitBox.js
# jd_cute_animals.js
# jd_cute_animalsCollect.js
# jd_cute_animalsMap.js
# jd_ry618.js
# adolf_flp.js
# adolf_superbox.js
# long_hby_lottery.js
# zy_618jc.js
# zooLongzhou.js
# zooSupershophf.js
# adolf_oneplus.js
# zooElecsport
# jd_star_store.js
# jx_pasture.js

##############################  京  东  到  家  ##############################
## jddj_fruit.js                京东到家 果园任务
## jddj_fruit_collectWater.js   京东到家 果园水车
## jddj_fruit_code.js           京东到家 果园获取互助码
## jddj_getPoints.js            京东到家 庄园领水滴
## jddj_bean.js                 京东到家 鲜豆任务
## jddj_plantBeans.js           京东到家 鲜豆庄园

## 京东到家需开通 "到家果园" 活动，自行挑选水果种植跟东东农场类似
## 不想薅这个APP的羊毛就忽略这些脚本，顺便把定时任务注释掉

## 京东到家账号环境变量（必填）：
## export JDDJ_CKPATH="/jd/scripts/jdCookie.js"       必须指定路径否则会报错

## 提交互助码 TG BOT
# @passerbybbot

##############################  定  义  下  载  代  理  （内置功能）  ##############################
if [[ ${EnableExtraShellProxyDownload} == true ]]; then
  DownloadJudgment=${ExtraShellProxyUrl}
else
  DownloadJudgment=
fi

##############################  作  者  昵  称  &  脚  本  地  址  &  脚  本  名  称  （必填）  ##############################

author_list="Public ZCY01 passerby-b LongZhuZhu Wenmoux panghu MoPoQAQ Andy ddo star261"

## Public
scripts_base_url_1=https://gitee.com/SuperManito/scripts/raw/master/
my_scripts_list_1="jx_cfdtx.js jdJxncTokens.js jd_necklace.js"



#SuperManito
https://gitee.com/SuperManito/scripts/tree/master/
#其他
https://github.com/YouHolmes/JdScripts
#燃情
https://github.com/smiek2221/scripts


## 京东试用
scripts_base_url_2=https://gitee.com/SuperManito/scripts/raw/master/
my_scripts_list_2="jd_try.js"

## 京东到家
## https://github.com/passerby-b/JDDJ
scripts_base_url_3=${DownloadJudgment}https://raw.githubusercontent.com/passerby-b/JDDJ/main/
my_scripts_list_3="jddj_fruit.js jddj_fruit_collectWater.js jddj_bean.js jddj_plantBeans.js jddj_getPoints.js jddj_fruit_code.js jddj_cookie.js"

## 龙王
## https://github.com/longzhuzhu/nianyu/tree/main/qx
scripts_base_url_4=${DownloadJudgment}https://raw.githubusercontent.com/longzhuzhu/nianyu/main/qx/
my_scripts_list_4="long_half_redrain.js long_super_redrain.js"

## Wenmoux

scripts_base_url_5=${DownloadJudgment}https://raw.githubusercontent.com/Wenmoux/scripts/wen/jd/
my_scripts_list_5="jd_SplitRedPacket.js jd_ddnc_farmpark.js"

## 柠檬/panghu
## https://github.com/panghu999/panghu
scripts_base_url_6=${DownloadJudgment}https://raw.githubusercontent.com/panghu999/panghu/master/
my_scripts_list_6="jd_sqdyj.js jd_sq.js jd_wsdlb.js"

## moposmall
## https://github.com/moposmall/Script/tree/main/Me
scripts_base_url_7=${DownloadJudgment}https://raw.githubusercontent.com/moposmall/Script/main/Me/
my_scripts_list_7="jx_mc_coin.js jx_mc_emptycabbage.js"

## Andy
## https://github.com/zsm85887823/AndyJD
scripts_base_url_8=${DownloadJudgment}https://raw.githubusercontent.com/zsm85887823/AndyJD/main/own/
my_scripts_list_8="Andy_sendBeans.js"

## ddo
## 
scripts_base_url_9=${DownloadJudgment}https://raw.githubusercontent.com/hyzaw/scripts/main/
my_scripts_list_9="ddo_pk.js"

## star261
## 
scripts_base_url_10=${DownloadJudgment}https://raw.githubusercontent.com/star261/jd/main/scripts/
my_scripts_list_10="star_dreamFactory_tuan.js"


## 免责声明：部分脚本的来源仓库启用了别人 FORK 或搬运的库并非原作者的官方渠道，能不能用我不知道，有什么问题也别问我

##############################  随  机  函  数  ##############################
rand() {
  min=$1
  max=$(($2 - $min + 1))
  num=$(cat /proc/sys/kernel/random/uuid | cksum | awk -F ' ' '{print $1}')
  echo $(($num % $max + $min))
}
cd ${ShellDir}
index=1
for author in $author_list; do
  echo -e "开始下载 $author 的活动脚本：\n"
  eval scripts_list=\$my_scripts_list_${index}
  eval url_list=\$scripts_base_url_${index}
  for js in $scripts_list; do
    eval url=$url_list$js
    echo $url
    eval name=$js
    echo $name
    wget -q --no-check-certificate $url -O scripts/$name.new

    if [ $? -eq 0 ]; then
      mv -f scripts/$name.new scripts/$name
      echo -e "更新 $name 完成...\n"
      croname=$(echo "$name" | awk -F\. '{print $1}')
      script_date=$(cat scripts/$name | grep "http" | awk '{if($1~/^[0-59]/) print $1,$2,$3,$4,$5}' | sort | uniq | head -n 1)
      if [ -z "${script_date}" ]; then
        cron_min=$(rand 1 59)
        cron_hour=$(rand 7 9)
        [ $(grep -c "$croname" ${ListCron}) -eq 0 ] && sed -i "/hangup/a${cron_min} ${cron_hour} * * * bash jd $croname" ${ListCron}
      else
        [ $(grep -c "$croname" ${ListCron}) -eq 0 ] && sed -i "/hangup/a${script_date} bash jd $croname" ${ListCron}
      fi
    else
      [ -f scripts/$name.new ] && rm -f scripts/$name.new
      echo -e "更新 $name 失败，使用上一次正常的版本...\n"
    fi
  done
  index=$(($index + 1))
done

##############################  自  定  义  命  令  ##############################

rm -rf ${ScriptsDir}/jd_superBrand.js && sed -i "/jd_superBrand/d" ${ListCron}
rm -rf ${ScriptsDir}/jd_limitBox.js && sed -i "/jd_limitBox/d" ${ListCron}
rm -rf ${ScriptsDir}/jd_cute_animals.js && sed -i "/jd_cute_animals/d" ${ListCron}
rm -rf ${ScriptsDir}/jd_cute_animalsCollect.js && sed -i "/jd_cute_animalsCollect/d" ${ListCron}
rm -rf ${ScriptsDir}/jd_cute_animalsMap.js && sed -i "/jd_cute_animalsMap/d" ${ListCron}
rm -rf ${ScriptsDir}/jd_ry618.js && sed -i "/jd_ry618/d" ${ListCron}
rm -rf ${ScriptsDir}/jd_qqtmy.js && sed -i "/jd_qqtmy/d" ${ListCron}
rm -rf ${ScriptsDir}/long_hby_lottery.js && sed -i "/long_hby_lottery/d" ${ListCron}
rm -rf ${ScriptsDir}/zy_618jc.js && sed -i "/zy_618jc/d" ${ListCron}
rm -rf ${ScriptsDir}/zooLongzhou.js && sed -i "/zooLongzhou/d" ${ListCron}
rm -rf ${ScriptsDir}/zooSupershophf.js && sed -i "/zooSupershophf/d" ${ListCron}
rm -rf ${ScriptsDir}/adolf_flp.js && sed -i "/adolf_flp/d" ${ListCron}
rm -rf ${ScriptsDir}/adolf_superbox.js && sed -i "/adolf_superbox/d" ${ListCron}
rm -rf ${ScriptsDir}/adolf_oneplus.js && sed -i "/adolf_oneplus/d" ${ListCron}
rm -rf ${ScriptsDir}/zooElecsport.js && sed -i "/zooElecsport/d" ${ListCron}
rm -rf ${ScriptsDir}/jd_star_store.js && sed -i "/jd_star_store/d" ${ListCron}
rm -rf ${ScriptsDir}/jx_pasture.js && sed -i "/jx_pasture/d" ${ListCron}
