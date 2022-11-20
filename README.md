# twitter-dynamic-evol-net

基于Twitter流构建的动态演化网络


生产环境：Python 3.6.3


数据信息：2014年的两起黑人运动事件（Ferguson事件、New York Chokehold事件）中的twitter转发网络信息及用户信息


数据来源：

Twitter API获取


数据文件说明：

Ferguson_nodes.csv   						------Ferguson事件的参与节点

Ferguson_edges.csv   						------Ferguson事件的边（每条表指代转发关系，无转发则表示为孤立节点）

fea_Ferguson_metrics.yaml					------Ferguson事件的参与节点的数值特征

fea_Ferguson_image_UserCategoryDic.yaml		------Ferguson事件的参与节点的头像类别

fea_Ferguson_image_sharpness_norm.yaml		------Ferguson事件的参与节点的头像锐度特征

fea_Ferguson_image_colors_norm.yaml			------Ferguson事件的参与节点的头像色彩特征

fea_Ferguson_image_category.yaml			------Ferguson事件的参与节点的头像类别	

fea_Ferguson_image_all.yaml					------Ferguson事件的参与节点的所有头像特征

Ferguson_profile_images.zip					------Ferguson事件的参与节点的头像【图像压缩包】

NYC_nodes.csv   							       ------NYC事件的参与节点

NYC_edges.csv   							       ------NYC事件的边（每条表指代转发关系，无转发则表示为孤立节点）

fea_NYC_metrics.yaml						      ------NYC事件的参与节点的数值特征

fea_NYC_image_UserCategoryDic.yaml			------NYC事件的参与节点的头像类别

fea_NYC_image_sharpness_norm.yaml			------NYC事件的参与节点的头像锐度特征

fea_NYC_image_colors_norm.yaml				------NYC事件的参与节点的头像色彩特征

fea_NYC_image_category.yaml				  	------NYC事件的参与节点的头像类别	

fea_NYC_image_all.yaml				  		------NYC事件的参与节点的所有头像特征

NYC_profile_images.zip					  	------NYC事件的参与节点的头像【图像压缩包】


数据用途说明：

新兴社交媒体为公众提供了分享意见、见解、经验和观点的工具和平台，也为媒体研究带来了海量的、高维的样本数据。

如何充分利用这些数据，无论是对计算科学还是对传播学来说，都是面向现实的挑战。

该研究工作瞄准国家“加快推动媒体融合发展”的需求，以国际社交媒体平台Twitter中的“事件参与者”作为切入点，
通过人工智能、量化分析、可视化等方法充分展现了事件的动态演变和参与群体特征，充分挖掘了数据样本的价值，
在成功实现“活跃参与者预测”这一目标的同时，展开了具有社会学意义的结果和讨论。具体如下：

其一，所采用的案例提供了一个网络热点事件中的参与群体的鲜活写照，为今后社会集体行动和社会运动的动态发展和演变预测，提供了一种可能性；

其二，论文所关注的问题具有历史延展性，是美国社会的长期冲突问题，也是全球范围社会冲突的重要组成。研究打破了惯常的只关注大节点或意见领袖的做法，创新性地将用户特征，尤其是图像特征与性格特征相对应，有助于弥补现有社会群体研究理论的盲点。

其三，所构建模型框架可迁移至其他社会学问题，如政治选举、国家博弈、民主主义、性别差异等主题研究，具有很好的延展性。


文章引用信息如下：
Wu X K, Zhao T F, Chen W N, et al. Toward Predicting Active Participants in Tweet Streams: A Case Study on Two Civil Rights Events[J]. IEEE Transactions on Knowledge & Data Engineering, 2022, 34(06): 2975-2987.


