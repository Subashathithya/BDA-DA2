SUBASH ATHITHYA - 22MIS1078

ABSTRACT:

In the rapidly evolving landscape of e-commerce, understanding customer behavior is crucial for enhancing user experience and optimizing marketing strategies. This study employs Self-Organizing Maps (SOM), a type of unsupervised neural network, to perform customer segmentation based on purchasing behavior. Using a dataset of e-commerce transactions, we first preprocess the data by filtering relevant features such as unique products purchased and unique categories engaged with by customers.

We then apply Min-Max scaling to normalize these features, followed by training the SOM to uncover distinct customer segments characterized by their purchasing patterns. Visualization of the SOM allows for intuitive identification of customer clusters, facilitating insights into varying customer behaviors.

Furthermore, we build a neural network to classify new customers into these segments, enabling personalized marketing approaches. The analysis reveals significant trends and patterns that can guide e-commerce businesses in targeting their marketing efforts more effectively, thereby enhancing customer satisfaction and loyalty. The findings underscore the potential of SOM in deriving actionable insights from complex customer data, providing a robust framework for segmentation in the e-commerce sector.

The E-commerce Behavior Data from a Multi-Category Store dataset contains detailed information on user behavior across various product categories in an e-commerce platform. The dataset tracks key user actions such as:

Product Views: Monitoring when users view products.

Cart Additions: Tracking items that users add to their shopping carts.

Purchases: Recording transactions when users purchase products.

This dataset is ideal for conducting customer segmentation based on behavioral patterns like browsing, purchasing frequency, and product preferences. It is particularly useful for tasks such as customer journey analysis, building recommendation systems, and marketing strategy optimization.

You can download the dataset here​(https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store).

TO HOW TO EXECUTE THE CODE:

To execute the implementation of customer segmentation using Self-Organizing Maps (SOM) in an e-commerce context, specific software and hardware requirements must be met. On the software side, utilizing platforms like Google Colab or Jupyter Notebook is recommended for ease of access to necessary libraries. Ensure you have a Python 3.x environment, and install essential libraries, including Pandas for data manipulation, NumPy for numerical operations, Matplotlib for data visualization, Minisom for SOM implementation, and scikit-learn and Keras for data preprocessing and building neural networks. For hardware, a dual-core CPU with at least 8 GB of RAM is the minimum requirement; however, a quad-core processor and 16 GB of RAM are ideal for handling larger datasets effectively. Additionally, while not essential, having a GPU can significantly enhance the speed of training complex neural networks, and Google Colab offers free access to GPU resources. Meeting these software and hardware specifications will facilitate the successful execution of your customer segmentation project, enabling you to derive valuable insights into customer behavior and optimize marketing strategies within the e-commerce sector.
