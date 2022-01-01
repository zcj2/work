# 12 月

## 日志记录

### 插入字典表ATTR_SPEC

```
INSERT INTO "SC_JKZT"."ATTR_SPEC"("ATTR_ID", "BUSI_TYPE_ID", "PAR_ATTR_ID", "ATTR_NBR", "ATTR_NAME", "ATTR_DESC", "DEFAULT_VALUE", "VALUE_FROM", "VALUE_TO", "IS_UNIQUE", "IS_NULLABLE", "ATTR_VALUE_DATA_TYPE", "IS_DANY_ATTR", "ATTR_VALUE_TYPE", "ATTR_FORMAT", "ATTR_LENGTH", "STATUS_CD", "CREATE_STAFF", "UPDATE_STAFF", "CREATE_DATE", "STATUS_DATE", "UPDATE_DATE", "REMARK", "EXT_ATTR_ID", "ATTR_CD", "ATTR_CODE", "ATTR_TYPE_CD", "ATTR_USAGE", "CHANGE_AGREEMENT_RATE", "EXP_DATE", "EXT_ATTR_CD", "FIELD_NAME", "HB_ATTR_ID", "IF_DEFAULT_VALUE", "INPUT_METHOD", "IS_BILLING_REF", "IS_INSTANTIATION", "MODULE_ID", "PARTY_ID", "PARTY_ROLE_ID", "SEND_BILL", "SEQ", "SPLIT_FLAG", "DISPLAY_FLAG", "EFF_DATE") VALUES ('1030423', NULL, NULL, 'INTERFACE_CODE', '接口编码', '日志接口编码', NULL, NULL, NULL, '0', '0', '1200', '0', '1000', NULL, NULL, '1000', NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, '1', NULL, NULL, NULL, NULL, '1', '1', NULL, NULL, NULL, NULL, NULL, NULL, '1', NULL, 'N', TO_DATE('2021-12-17 15:12:34', 'SYYYY-MM-DD HH24:MI:SS'));
```

### 插入字典表 ATTR_VALUE

```
INSERT ALL
INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ) VALUES (12101,1030423,'4A审计日志','4A审计日志','12101','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12102,1030423,'生成访问外系统页面的token','生成访问外系统页面的token','12102','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12103,1030423,'申请boss帐号日志','申请boss帐号日志','12103','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12104,1030423,'调用4A接口4A身份证号验证','调用4A接口4A身份证号验证','12104','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12105,1030423,'调用4A接口检查账号密码接口日志','调用4A接口检查账号密码接口日志','12105','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12106,1030423,'拓客校验内部、渠道人员接口','拓客校验内部、渠道人员接口','12106','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12107,1030423,'调用统一认证token校验接口日志','调用统一认证token校验接口日志','12107','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12108,1030423,'ESOP同步人员角色接口','ESOP同步人员角色接口','12108','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12109,1030423,'调用boss接口检查boss账号接口日志','调用boss接口检查boss账号接口日志','12109','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12110,1030423,'国信查询任务数量接口','国信查询任务数量接口','12110','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (121121,1030423,'调用4A接口更新主账号最后登录时间','调用4A接口更新主账号最后登录时间','121121','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12112,1030423,'4A工号创建','4A工号创建','12112','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12113,1030423,'调用集客大厅获取H5URL接口日志','调用集客大厅获取H5URL接口日志','12113','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12114,1030423,'校验外访问外系统页面的token','校验外访问外系统页面的token','12114','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12115,1030423,'boss登陆日志','boss登陆日志','12115','1000',1,1) 
 INTO ATTR_VALUE (ATTR_VALUE_ID,ATTR_ID,ATTR_VALUE_NAME,ATTR_VALUE_DESC,ATTR_VALUE,STATUS_CD,ATTR_VALUE_SORT,SEQ)  VALUES (12116,1030423,'4A新审计日志','4A新审计日志','12116','1000',1,1) 
select 1 from dual;
```

### 修改二级角色表

1. APPROVAL_ROLE表添加字段

```
ALTER TABLE "SC_JKZT"."APPROVAL_ROLE" 
ADD ("ARE_LEVEL" NUMBER(2,0));

COMMENT ON COLUMN "SC_JKZT"."APPROVAL_ROLE"."ARE_LEVEL" IS '区域级别:1.省,2.市3,区县'
```

2. 设置value  ps: 可以复制表

   ```
   ```

   

2. 修改APPROVAL_ROLE_IMAGE表结构添加are_level字段

4. 修改approval_role_trigger

   ```
   CREATE OR REPLACE TRIGGER approval_role_trigger AFTER
       DELETE OR INSERT OR UPDATE ON approval_role
       FOR EACH ROW
   BEGIN
       IF inserting THEN
           INSERT INTO approval_role_image (
               ID,
               ROLE_CODE,
               ROLE_NAME,
               ROLE_LEVEL,
               PARENT_ROLE_CODE,
               STATUS_CD,
               TIER,
               IS_SINGLE,
               ARE_LEVEL,
               image_id,
               sync_type,
               sync_status,
               sync_date
           ) VALUES (
               :new.ID,
               :new.ROLE_CODE,
               :new.ROLE_NAME,
               :new.ROLE_LEVEL,
               :new.PARENT_ROLE_CODE,
               :new.STATUS_CD,
               :new.TIER,
               :new.IS_SINGLE,
               :new.ARE_LEVEL,
               APPROVAL_role_SEQ.NEXTVAL,
               'insert',
               'N',
               SYSDATE
           );
   
       ELSIF updating THEN
           INSERT INTO approval_role_image (
               ID,
               ROLE_CODE,
               ROLE_NAME,
               ROLE_LEVEL,
               PARENT_ROLE_CODE,
               STATUS_CD,
               TIER,
               IS_SINGLE,
               ARE_LEVEL,
               image_id,
               sync_type,
               sync_status,
               sync_date
           ) VALUES (
               :new.ID,
               :new.ROLE_CODE,
               :new.ROLE_NAME,
               :new.ROLE_LEVEL,
               :new.PARENT_ROLE_CODE,
               :new.STATUS_CD,
               :new.TIER,
               :new.IS_SINGLE,
               :new.ARE_LEVEL,
               APPROVAL_role_SEQ.NEXTVAL,
               'update',
               'N',
               SYSDATE
           );
   
       ELSIF deleting THEN
           INSERT INTO approval_role_image (
               ID,
               image_id,
               sync_type,
               sync_status,
               sync_date
           ) VALUES (
               :old.ID,
               APPROVAL_role_SEQ.NEXTVAL,
               'delete',
               'N',
               SYSDATE
           );
   
       END IF;
   END approval_role_trigger;
   
   ```

   

3. 复制are_level到APPROVAL_ROLE_IMAGE

   ```
   -- 复制表APPROVAL_ROLE_IMAGE
   CREATE TABLE APPROVAL_ROLE_IMAGE_COPY1 AS SELECT * FROM APPROVAL_ROLE_IMAGE
   
   SELECT * FROM APPROVAL_ROLE_IMAGE_COPY1 ORDER BY ID;
   
   -- 复制are_level 到copy表
   UPDATE APPROVAL_ROLE_IMAGE_COPY1 A set A.ARE_LEVEL = (SELECT ARE_LEVEL FROM APPROVAL_ROLE B WHERE A.ID=B.ID)
   
   -- 复制are_level到 role_image
   UPDATE APPROVAL_ROLE_IMAGE A set A.ARE_LEVEL = (SELECT ARE_LEVEL FROM APPROVAL_ROLE B WHERE A.ID=B.ID)
   
   SELECT * FROM APPROVAL_ROLE ORDER BY ARE_LEVEL;
   ```

   
   
   6. 测试触发器是否成功
   
   ```
   SELECT * FROM APPROVAL_ROLE ORDER BY ID DESC;
   
   INSERT INTO APPROVAL_ROLE VALUES (85,'TEST','TEST',2,'TEST',1000,1,NULL,2);
   
   DELETE FROM APPROVAL_ROLE WHERE ID=85;
   
   SELECT * FROM APPROVAL_ROLE_IMAGE ORDER BY ID DESC;
   ```
   
   # 
   
   

## 指南针pc

添加菜单 指南针pc端 [iframe]http://192.168.8.4/fishx-base         ps: ip地址填写适当的指南针pc端地址,后缀包括"fishx-base"
