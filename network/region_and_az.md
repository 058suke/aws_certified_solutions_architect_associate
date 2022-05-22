# リージョンとアベイラビリティゾーン

## リージョン

- AWSがサービスを提供している国や地域のこと。

- リージョン同士は地理的に離れている。

![](/Users/058suke/Library/Application%20Support/marktext/images/2022-05-17-01-35-55-image.png)

> 画像: [AWS グローバルインフラストラクチャ | AWS](https://aws.amazon.com/jp/about-aws/global-infrastructure/)

## アベイラビリティゾーン（AZ）

- リージョン内に含まれる複数のデータセンターの集まりのこと。
- AZは、地理的・電源的に独立した場所に配置されている。
  - 自然災害による障害に対し、別のAZに影響がないように離れた場所に配置されている。
  - 独立した場所に配置されているが、各AZ間は高速なネットワーク回線で接続されているため遅延はほぼない。

### マルチAZ

- 耐障害性を高め、システムの可用性を高めるために1つのAZのみでシステム構築するのではなく、複数のAZにシステムを構築すること。

    ![](/Users/058suke/Desktop/aws_certified_solutions_architect_associate/network/multi_az_example.png)

> 画像: マルチAZ例
> 
> - ALBから2つのAZにそれぞれ配置されたEC2インスタンス(Webサーバー)に負荷分散させている。








