Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [dbt community](http://community.getbdt.com/) to learn from other analytics engineers
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices

---

# dbt run -m dim_customers
モデルを指定してrunする

# config

```
{{
  config(
    materialized='table'
  )
}}
```

これを指定すると、Snowflake上にテーブルが作成できる。  
指定しないと、テーブルではなくviewが作成される


# commands
`dbt docs generate`