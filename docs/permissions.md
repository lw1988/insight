|路由端点|功能描述|具备访问权限的角色(admin具备所有权限)
|-----|-----|------|
|admin.index|管理后台－首页|安全管理员，安全人员
|admin.login_user_read|管理后台－用户查看|-
|admin.login_user_related|管理后台－用户关联|-
|admin.login_user_modify|管理后台－用户修改|-
|admin.login_user_delete|管理后台－用户删除|-
|admin.role_add|管理后台－角色增加|-
|admin.role_read|管理后台－角色读取|-
|admin.role_modify|管理后台－角色修改|-
|admin.perm_modify|管理后台－权限修改|-
|admin.role_perm_delete|管理后台－角色权限删除|-
|admin.depart_add|管理后台－部门增加|安全管理员
|admin.depart_read|管理后台－部门查看|安全管理员
|admin.depart_modify|管理后台－部门修改|安全管理员
|admin.depart_delete|管理后台－部门删除|安全管理员
|admin.user_add|管理后台－员工增加|安全管理员
|admin.user_read|管理后台－员工查看|安全管理员
|admin.user_modify|管理后台－员工修改|安全管理员
|admin.user_delete|管理后台－员工删除|安全管理员
|admin.assets_add|管理后台－资产增加|安全管理员，安全人员
|admin.assets_add_ajax|管理后台－资产增加AJAX|安全管理员，安全人员
|admin.assets_read|管理后台－资产查看|安全管理员，安全人员
|admin.assets_modify|管理后台－资产修改|安全管理员，安全人员
|admin.assets_delete|管理后台－资产删除|安全管理员
|admin.vul_type_add|管理后台－漏洞类型增加|安全管理员
|admin.vul_type_read|管理后台－漏洞类型查看|安全管理员
|admin.vul_type_modify|管理后台－漏洞类型修改|安全管理员
|admin.vul_type_delete|管理后台－漏洞类型删除|安全管理员
|src.vul_report_delete|SRC－漏洞报告删除|安全管理员
|src.vul_report_admin_edit|SRC－漏洞报告管理编辑|-
|src.vul_report_review|SRC-漏洞报告审核|安全管理员
|src.vul_report_review_ajax|SRC-漏洞报告审核AJAX|安全管理员
|src.vul_report_send_email|SRC-漏洞报告发送邮件|安全管理员
|src.vul_report_known|SRC-漏洞报告－已知悉提交|安全管理员，普通用户
|src.vul_report_dev_finish|SRC-漏洞报告－申请复测|安全管理员，普通用户
|src.vul_report_vul_cata|SRC-漏洞报告－漏洞层面提交|安全管理员，安全人员
|src.vul_report_attack_check|SRC-漏洞报告－攻击发现提交|安全管理员，安全人员
|src.vul_report_retest_result|SRC-漏洞报告－复测结果提交|安全管理员，安全人员
|src.vul_report_retest_ajax|SRC-漏洞报告－复测结果提交AJAX|安全管理员，安全人员
|src.vul_report_add|SRC-漏洞报告-增加|安全管理员，安全人员
|src.upload_img|SRC-漏洞报告－上传|安全管理员，安全人员
|src.vul_review_list|SRC-漏洞报告－未审核列表|安全管理员，安全人员
|src.assets_read|SRC-资产查看|安全管理员，安全人员，普通用户
|src.assets_add|SRC-资产增加|安全管理员，安全人员
|src.assets_add_ajax|SRC－资产增加AJAX|安全管理员，安全人员
|src.assets_modify|SRC-资产修改|安全管理员，安全人员
|main.index_count|MAIN-漏洞报告统计|-
|main.index_stats_time|MAIN-漏洞处理时间统计|-
|drops.manager|SRC－知识库管理|安全管理员，安全人员