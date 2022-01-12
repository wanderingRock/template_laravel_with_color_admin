# template_laravel_with_color_admin



### Step.1 使用color-admin模板 搭建laravel版本
---
將模板   
color_admin_v4.6\admin\template 下的 template_laravel資料夾拉到您的環境   


### Step.2 相關安裝
---
```
composer install
npm install --force
npm run dev
```
途中 composer install 有遇到1個問題 下更新並重新install
```
composer self-update --1
composer install
```
### Step.3 移動color的assets到專案內
```
<!-- copy the following folder-->
/admin/template/assets/img
 
<!-- paste it into laravel folder -->
/admin/template/template_laravel/public/assets/img
```

參考網址 => https://seantheme.com/color-admin/documentation/index_laravel.html
