修改部分
> * 修复乱码问题，生成文件一律转为utf-8
> * 修改配置catalog时，生成代码为Schema..table的问题
> * 修改生成注释类，将英文注释去掉，改为数据库字段注释
> org.mybatis.generator.api.IntrospectedTable，生成的文件结尾修正。eg:TBank.java,TBankCriteria.java,TBankMapper.java,TBankMapper.xml
