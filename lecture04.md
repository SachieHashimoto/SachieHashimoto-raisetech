# 第4回課題提出  

  
## ・VPC作成  
  
VPC構成内容  
![Image 01](images/vpc.png) 
  
## ・EC2作成  
 
EC2構成内容  
  
![Image 02](images/EC2-1.png)  
  
![Image 03](images/EC2-2.png) 
  

## ・RDS作成
  
RDS構成内容  
  
![Image 04](images/rds-1.png)
  
![Image 05](images/rds-2.png) 

### 追記 セキュリティグループの詳細
「rds-ec2-1」  

![Image 07](images/rds-ec2-1.png)  
  

「sachi-raisetech-db 1-sg 」インバウンド
    
![Image 08](images/sachi-raisetech-db1-sg-inbound.png) 
  

「sachi-raisetech-db  1-sg 」アウトバウンド
   
![Image 09](images/sachi-raisetech-db1-sg-outbound.png) 

### 追記　サブネットグループの詳細
  
![Image 10](images/subnet-0dd10cfa9726a1574.png)  
![Image 11](images/subnet-0847f4621759c8a10.png)  
  
## ・EC2からRDSに接続
  
![Image 06](images/ec2-rds.png) 


## ・課題を終えての感想  
とても時間をかけてしまった。  
初めよくわからないまま一通り作ったが、EC2にアクセスできず、VPCのサブネット構成もRDSの作り方を間違えていたので変わってしまっていたので一旦すべて削除した。  
AWSやインターネット技術の入門書を色々と読んでからは、ある程度判断しながら再作成できたように思う。  
今回の課題からMACのターミナルを使用しました。  
エクスプローラと違い、『.ssh』等の設定ファイルが見えなくなっていることもわからず、キーペアの保存や設定にも手こずってしまった。
EC2に接続できた時はとても達成感を感じた。  
cloud９を使っていた時は、そもそもターミナルというものがよく理解できたなかった。  
自身のPCでCUIとGUIの操作の違いを実感できて感動した。  
そもそもcloud９が仮想マシンだということもやっと理解できたように思う。