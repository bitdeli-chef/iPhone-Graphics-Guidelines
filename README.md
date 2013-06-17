#iPhone Graphics Guidelines

*Note to reader: If you have anything to add, please create a pull request!***All graphics** should have their width and height rounded up or down - there shouldn’t be any graphics that have dimensions of 41x43 px for example, it should be 40x45px in this case, or 40x40/45x45 depending on the shape of the image.**Buttons** must have a default state (how they will look normally), and a selected/highlighted state (how they will look when the user has tapped on it), as separate images. **All graphics** must be provided in legacy and retina formats. Retina formatted graphics have “@2x” appended to their filename, and are twice the size (dimension) of the legacy images.**Application Icons** need to be named and sized accordingly pursuant to the Apple Custom Icon and Image Creation Guidelines:<table>
    <thead>
    <tr>
    <th>Filename</td>
    <th>Dimensions</td>
    <th>Description</td>
    </tr>
    </thead>
    <tr>
    <td>Icon.png</td>
    <td>57x57px</td>
    <td>The icon displayed on the homescreen on legacy devices.</tr>
    <td>Icon@2x.png</td>
    <td>114x114px</td>
    <td>The icon displayed on the homescreen on retina devices.</tr>
    <td>Icon-Small.png</td>
    <td>29x29px</td>
    <td>Settings Icon</tr>
    <td>Icon-Small@2x.png</td>
    <td>58x58px</td>
    <td>Retina Settings Icon</tr>
    <td>Icon-Small-50.png</td>
    <td>57x57px</td>
    <td>Spotlight search results icon</tr>
    <td>Icon-Small-50.@2xpng</td>
    <td>50x50px</td>
    <td>Spotlight search results icon retina</tr>
    <td>iTunesArtwork.png</td>
    <td>100x100px</td>
    <td>App icon to be displayed on the App Store</tr>
    <td>iTunesArtwork@2x.png</td>
    <td>57x57px</td>
    <td>Retina version of the App icon to be displayed on the App Store</tr>
</table>
   **Launch screen** graphics are displayed when the app is launched, and generally consist of the application’s logo and perhaps a few words about the app. It is sized accordingly, pursuant to the same guidelines:<table>
	<thead>
	<tr>
	<th>Filename</th>
	<th>Dimensions</th>
	</tr>
	</thead>
	<tr>
	<td>Default.png</td>
	<td>320x480px</td>
	</tr>
	<tr>
	<td>Default@2x.png</td>
	<td>640x960px</td>
	</tr>
	<tr>
	<td>Default-568h@2x.png</td>
	<td>640x1136px</td>
	</tr>
</table>