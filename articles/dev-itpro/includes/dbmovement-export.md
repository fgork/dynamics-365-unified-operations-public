## Self-service database export

From your sandbox environment details page, click the **Maintain** menu and then select **Move database**.  
<img src="../database/media/DBMovement_Menu.png" width="400px" alt="Move database menu" />

A slider pane will open on the page where you can use the **Export database** action.
<br/>
<img src="../database/media/Export_Menu.png" width="400px" alt="Export database menu"/>

The environment will be unavailable for other servicing operations such as Sandbox Refresh or Package Deployment during this time. The source environment will be usable from a Dynamics user perspective.  

After the export operation completes successfully, sign off on the servicing operation on your **Environment details** page. You can then see the asset in your **Asset Library** in the **Database backups** section.
<img src="../database/media/AssetLibrary_Backups.png" width="800px" alt="Asset library backup files"/>

The .bacpac files are stored here and can be manually downloaded to your Tier 1 developer environments for import. In the future, Microsoft will provide APIs to trigger the export action, as well as list the available backup files in your asset library. This includes the secured URL for automatically downloading a backup asset file or copying it directly to your own secure blob storage using Microsoft Azure Storage SDKs.
