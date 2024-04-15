# Hanka - blueprint

----
### sequelize
add migration `npx sequelize-cli seed:generate --name demo-user`

add model `npx sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string `

run migrations: `npx sequelize-cli db:migrate`