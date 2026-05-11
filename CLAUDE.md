heckout -b gfb-v10-sp3-gfb-031 origin/gfb-v10-sp3-gfb-031
切换到到 V11 分支
git checkout -b gfb-v11-gfb origin/gfb-v11-gfb


上述是一个skills

#按照spec文件中changlog中第一个changelog进行commit：git commit -a -m "[type#id]comment"
example：
%changelog
* Sat May 09 2026 dingcaokai <dingcaokai@kylinos.cn> - 4.2.23-6.p03.gfb027
- Type: bug
- ID: [#551507] yum安装不存在的包kernel-tools-libs提示信息异常
- SUG:N/A
- DES:kylin-yum-optimize-8.patch

%changelog
* Sat May 09 2026 dingcaokai <dingcaokai@kylinos.cn> - 4.2.23-6.p03.gfb027
- Type: bug
- ID: [bug#551507] yum安装不存在的包kernel-tools-libs提示信息异常
- SUG:N/A
- DES:kylin-yum-optimize-8.patch

%changelog
* Sat May 09 2026 dingcaokai <dingcaokai@kylinos.cn> - 4.2.23-6.p03.gfb027
- Type: bug
- ID: [551507] yum安装不存在的包kernel-tools-libs提示信息异常
- SUG:N/A
- DES:kylin-yum-optimize-8.patch


git commit -a -m "[bug#551507]yum安装不存在的包kernel-tools-libs提示信息异常"

#推动，进行询问
推送到 V10 分支
git push origin gfb-v10-sp3-gfb-031:refs/for/gfb-v10-sp3-gfb-031
推送到 V11 分支
git push origin gfb-v11-gfb:refs/for/gfb-v11-gfb



这是另一个skills
