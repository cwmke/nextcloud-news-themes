# Nextcloud News Themes
This is a central repository to share custom themes created for the [Nextcloud News](https://github.com/nextcloud/news) webapp. Feel free to make pull requests to add your own. 
Changes should be limited to the custom.css file located in nextcloud/apps/news/css/custom.css. If not, include clear instructions on how to install and remove your customizations at the top of your theme.css file.

## Installation 
1. git clone https://github.com/cwmke/nextcloud-news-themes.git
2. cd nextcloud-news-themes/themes
3. sudo cp THEMENAME.css /usr/share/webapps/nextcloud/apps/news/css/custom.css
4. sudo chown 644 /usr/share/webapps/nextcloud/apps/news/css/custom.css
5. Enjoy!

### There is no guarentee that themes will not break your cloud. They shouldn't but the risk is entirely yours to take.

## Theme Previews

### Blue and Gray Theme
![Image of Blue and Gray Theme](https://raw.githubusercontent.com/cwmke/nextcloud-news-themes/master/images/blue_and_gray.jpg)
![Image of Blue and Gray Theme With Open Article](https://raw.githubusercontent.com/cwmke/nextcloud-news-themes/master/images/blue_and_gray_article.png)

### Submitting Themes
- Submit a pull request with your theme in the themes folder and your images in the images folder (pretty easy 😉).
- Make sure to include 2 screenshots with your pull requests. The naming should be identical to your theme name and should be added to the README.md file. 

### Example Theme Named "Test One", 

**Theme Name:** test_one.css

**Image Names:** test_one.jpg test_one_article.jpg
