 IDRBT web page words in wordcloud

# Code 

from wordcloud import WorkCloud
import matplotlib.pyplot as plt
text ="        "
cloud = WordCloud (background_color="white").generate(text)
plt.imshow(cloud)
plt.axis('off')
plt.show()


Build in pycharm by importing 
Matplotlib and workcloud