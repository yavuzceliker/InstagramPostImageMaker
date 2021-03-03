<center><h1>Instagram Post Image Maker</h1></center>
It will be very useful if you are creating a post on a fixed draft for your social media account. 
<meta name='keywords' content='Social API, Github Social Media, Instagram, Twitter, API, Sosyal Medya API, Sosyal, Post Image Maker, Instagram POST'>

You can create pictures from the prepared API with get or post methods.
<!--
  Title: Social Media Post Image Maker
  Description: Create fast and automatic social media post image.
  Author: yavuzceliker
  -->
<table>
<tr>
<th colspan="3"><h4><center>Sample pictures</center></h4></th>
</tr>
<tr>
<td><img src="https://social.yavuzceliker.com.tr/withnetworkimage?imageUrl=https://i.pinimg.com/originals/69/a4/2f/69a42ff7408eeb9d1d501640fc592785.jpg&logoUrl=https://converter.yavuzceliker.com.tr/Assets/Images/logo.png&blurRatio=7&darknessRatio=23&text=Social%20Media%20Post%20Image%20Creator&font=MV%20Boli&color=skyblue&bold=true&italic=false&shadow=true&verticalAlignment=Middle&horizontalAlignment=Center" ></td>
<td><img src="https://social.yavuzceliker.com.tr/withnetworkimage?imageUrl=https://i2.wp.com/bedirhaber.com/wp-content/uploads/2019/08/G%C3%BCzel-bir-resim.jpg?fit=480%2C480&ssl=1&logoUrl=https://converter.yavuzceliker.com.tr/Assets/Images/logo.png&blurRatio=16&darknessRatio=90&text=Social%20Media%20Post%20Image%20Creator%20Sample%20Picture&font=Courier%20New&color=orange&bold=true&italic=false&shadow=true&verticalAlignment=Top&horizontalAlignment=Right" ></td>
<td><img src="https://social.yavuzceliker.com.tr/withnetworkimage?imageUrl=https://www.arthipo.com/artblog/wp-content/uploads/2017/10/akrilik-boya-teknikleri-1080x675.jpg&logoUrl=https://pngimg.com/uploads/github/github_PNG15.png&blurRatio=0&darknessRatio=0&text=Social%20Media%20Post%20Image%20Creator&font=Courier%20New&color=deeppink&bold=true&italic=true&shadow=true&verticalAlignment=Bottom&horizontalAlignment=Center" ></td>
</tr>
</table>

### Demo
Demo Link: <a href="https://yavuzceliker.github.io/InstagramPostImageMaker">yavuzceliker.github.io/InstagramPostImageMaker</a>

### How To Use API
API Root: https://social.yavuzceliker.com.tr/

<table>
<tr>
<th colspan="3"><h5><center>Parameters and Values</center></h5></th>
</tr>
<tr>
<td>Parameter Name</td>
<td>Info</td>
<td>Value</td>
</tr>
<tr>
<td>imageUrl <b style="color:red;">**</b></td>
<td>Background image URL address.</td>
<td>string</td>
</tr>
<tr>
<td>logoUrl <b style="color:red;">**</b></td>
<td>Logo image URL address.</td>
<td>string</td>
</tr>
<tr>
<td>text <b style="color:red;">**</b></td>
<td>Text on the picture.</td>
<td>string</td>
</tr>
<tr>
<td>blurRatio</td>
<td>The blur ratio of the picture. </td>
<td>int (0-400)</td>
</tr>
<tr>
<td>darknessRatio</td>
<td>The darkness ratio of the picture.</td>
<td>int (0-255)</td>
</tr>
<tr>
<td>font</td>
<td>Font family of the text in the picture.</td>
<td>string List is List is <a href="http://social.yavuzceliker.com.tr/fontList">here</a>.</td>
</tr>
<tr>
<td>color</td>
<td>The color of the text in the picture. </td>
  <td>string List is <a href="http://social.yavuzceliker.com.tr/colorList">here</a>.</td>
<tr>
<td>bold</td>
<td>Font is bold? </td>
<td>bool (true, false)</td>
</tr>
<tr>
<td>italic</td>
<td>Font is italic? </td>
<td>bool (true, false)</td>
</tr>
<tr>
<td>shadow</td>
<td>Font have a shadow?</td>
<td>bool (true, false)</td>
</tr>
<tr>
<td>verticalAlignment</td>
<td>Vertical position of the text. </td>
<td>string (top, middle, bottom)</td>
</tr>
<tr>
<td>horizontalAlignment</td>
<td>Horizontal position of the text. </td>
<td>string (left, center, right)</td>
</tr>
</table>
<b style="color:red;">**</b> Required parameters.

### Sample Usages
1. Only imageUrl, logoUrl and text<br>
https://social.yavuzceliker.com.tr/?imageUrl=https://www.yavuzceliker.com.tr/Assets/Images/gonderiResim/6.jpg&logoUrl=https://yavuzceliker.com.tr/assets/images/logo.png&text=SayHello
2. imageUrl, logoUrl, text and any parameter<br>
https://social.yavuzceliker.com.tr/?imageUrl=https://www.yavuzceliker.com.tr/Assets/Images/gonderiResim/6.jpg&logoUrl=https://yavuzceliker.com.tr/assets/images/logo.png&text=SayHello&horizontalAlignment=center
3. All parameters<br>
https://social.yavuzceliker.com.tr/?imageUrl=https://www.yavuzceliker.com.tr/Assets/Images/gonderiResim/6.jpg&logoUrl=https://yavuzceliker.com.tr/assets/images/logo.png&text=SayHello&font=Microsoft%20Sans%20Serif&color=Red&bold=true&italic=true&shadow=true&verticalAlignment=top&horizontalAlignment=right&blurRatio=5&darknessRatio=100
