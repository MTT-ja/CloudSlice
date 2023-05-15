# Azure AD テナントを作成する


1. ほかの AAD テナントに紐づけられておらず、Microsoft 365 評価版の有効化などに使用していない Microsoft アカウントを用意します。（必要であれば新しい Microsoft アカウントを作成してください）
1. ブラウザを Inprivate モードなどで起動して https://account.windowsazure.com/organization にアクセスして Microsoft アカウントの ID (メールアドレス) を入力します。
  ![image](https://github.com/dakozu/CloudSlice/assets/32472054/4f640735-4245-494f-be14-162954e05474)

1. 入力した MS アカウントが既に他の AAD テナントに紐づけられていなければ アカウントのセットアップ ボタンが表示されるのでクリックします。
  ![image](https://github.com/dakozu/CloudSlice/assets/32472054/1dc9966b-04af-4f10-8a60-650aac6e7fa6)
  
1. テナントの作成に必要な情報の入力を求められるので、各情報を入力して 次へ をクリックします。
  ![image](https://github.com/dakozu/CloudSlice/assets/32472054/7c1514a9-04e4-4bfe-8c7b-e63840ed1290)

1. SMS か 電話認証で本人確認を行います。
  ![image](https://github.com/dakozu/CloudSlice/assets/32472054/0e519894-6b97-406f-8b61-d48a5879e3de)

1. 作成するテナントの管理者 ID とドメイン名等を入力して 次へ をクリックします。
   ※ドメイン名はほかのユーザーに使用されていない文字列を指定する必要があります
   ![image](https://github.com/dakozu/CloudSlice/assets/32472054/b6c35e82-696a-46ab-8228-68f59bc886f4)
   
1. これで Azure AD テナントの作成は完了です。
   ![image](https://github.com/dakozu/CloudSlice/assets/32472054/11d6c969-7f9d-4334-8493-2078c3d59060)

1. ブラウザで Azure ポータル (https://portal.azure.com/) にアクセスして作成したテナントの管理者でログインし、
   Azure Active Directory を検索して表示するとテナントの情報を確認することができます。
   ![image](https://github.com/dakozu/CloudSlice/assets/32472054/dfcb6c12-528a-4bb5-87eb-31709b107353)
