---
title:  "CLASS OPENCART 2.1.0.2"
categories: opencart
permalink: opencart-class.html
tags: [news]
datatable: true
---

{% include image.html file="/images/ClassDiagram_Opencart_small.png" url="/images/ClassDiagram_Opencart.png" alt="Class Opencart 2.1.0.2" caption="Class Diagram Opencart 2.1.0.2" %}

### admin\controller\
#### analytics\google_analytics.php #class ControllerAnalyticsGoogleAnalytics extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### captcha\basic_captcha.php #class ControllerCaptchaBasicCaptcha extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### captcha\google_captcha.php #class ControllerCaptchaGoogleCaptcha extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### catalog\attribute.php #class ControllerCatalogAttribute extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function autocomplete()
#### 
#### catalog\attribute_group.php #class ControllerCatalogAttributeGroup extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### catalog\category.php #class ControllerCatalogCategory extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function repair()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*protected function validateRepair()
*public function autocomplete()
#### 
#### catalog\download.php #class ControllerCatalogDownload extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function upload()
*public function autocomplete()
#### 
#### catalog\filter.php #class ControllerCatalogFilter extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function autocomplete()
#### 
#### catalog\information.php #class ControllerCatalogInformation extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### catalog\manufacturer.php #class ControllerCatalogManufacturer extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function autocomplete()
#### 
#### catalog\option.php #class ControllerCatalogOption extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function autocomplete()
#### 
#### catalog\product.php #class ControllerCatalogProduct extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function copy()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*protected function validateCopy()
*public function autocomplete()
#### 
#### catalog\recurring.php #class ControllerCatalogRecurring extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function copy()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*protected function validateCopy()
#### 
#### catalog\review.php #class ControllerCatalogReview extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### common\column_left.php #class ControllerCommonColumnLeft extends Controller
*public function index()
#### 
#### common\dashboard.php #class ControllerCommonDashboard extends Controller
*public function index()
#### 
#### common\filemanager.php #class ControllerCommonFileManager extends Controller
*public function index()
*public function upload()
*public function folder()
*public function delete()
#### 
#### common\footer.php #class ControllerCommonFooter extends Controller
*public function index()
#### 
#### common\forgotten.php #class ControllerCommonForgotten extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### common\header.php #class ControllerCommonHeader extends Controller
*public function index()
#### 
#### common\login.php #class ControllerCommonLogin extends Controller
*private $error
*public function index()
*protected function validate()
*public function check()
#### 
#### common\logout.php #class ControllerCommonLogout extends Controller
*public function index()
#### 
#### common\menu.php #class ControllerCommonMenu extends Controller
*public function index()
#### 
#### common\profile.php #class ControllerCommonProfile extends Controller
*public function index()
#### 
#### common\reset.php #class ControllerCommonReset extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### common\sass.php #class ControllerCommonSass extends Controller
*public function index()
#### 
#### common\stats.php #class ControllerCommonStats extends Controller
*public function index()
#### 
#### customer\customer.php #class ControllerCustomerCustomer extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function approve()
*public function unlock()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*protected function validateApprove()
*protected function validateUnlock()
*public function login()
*public function history()
*public function addHistory()
*public function transaction()
*public function addTransaction()
*public function reward()
*public function addReward()
*public function ip()
*public function autocomplete()
*public function customfield()
*public function address()
#### 
#### customer\customer_group.php #class ControllerCustomerCustomerGroup extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### customer\custom_field.php #class ControllerCustomerCustomField extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### dashboard\activity.php #class ControllerDashboardActivity extends Controller
*public function index()
#### 
#### dashboard\chart.php #class ControllerDashboardChart extends Controller
*public function index()
*public function chart()
#### 
#### dashboard\customer.php #class ControllerDashboardCustomer extends Controller
*public function index()
#### 
#### dashboard\map.php #class ControllerDashboardMap extends Controller
*public function index()
*public function map()
#### 
#### dashboard\online.php #class ControllerDashboardOnline extends Controller
*public function index()
#### 
#### dashboard\order.php #class ControllerDashboardOrder extends Controller
*public function index()
#### 
#### dashboard\recent.php #class ControllerDashboardRecent extends Controller
*public function index()
#### 
#### dashboard\sale.php #class ControllerDashboardSale extends Controller
*public function index()
#### 
#### design\banner.php #class ControllerDesignBanner extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### design\layout.php #class ControllerDesignLayout extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### error\not_found.php #class ControllerErrorNotFound extends Controller
*public function index()
#### 
#### error\permission.php #class ControllerErrorPermission extends Controller
*public function index()
*public function check()
#### 
#### extension\analytics.php #class ControllerExtensionAnalytics extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*protected function getList()
*protected function validate()
#### 
#### extension\captcha.php #class ControllerExtensionCaptcha extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*protected function getList()
*protected function validate()
#### 
#### extension\feed.php #class ControllerExtensionFeed extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*protected function getList()
*protected function validate()
#### 
#### extension\fraud.php #class ControllerExtensionFraud extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*protected function getList()
*protected function validate()
#### 
#### extension\installer.php #class ControllerExtensionInstaller extends Controller
*private $error
*public function index()
*public function upload()
*public function unzip()
*public function ftp()
*public function sql()
*public function xml()
*public function php()
*public function remove()
*public function clear()
#### 
#### extension\modification.php #class ControllerExtensionModification extends Controller
*private $error
*public function index()
*public function delete()
*public function refresh()
*public function clear()
*public function enable()
*public function disable()
*public function clearlog()
*protected function getList()
*protected function validate()
#### 
#### extension\module.php #class ControllerExtensionModule extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*public function delete()
*protected function getList()
*protected function validate()
*protected function validateDelete()
#### 
#### extension\openbay.php #class ControllerExtensionOpenbay extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*public function manage()
*public function updateTest()
*public function update()
*public function updateV2()
*public function patch()
*public function notifications()
*public function version()
*public function faq()
*public function faqDismiss()
*public function faqClear()
*public function getOrderInfo()
*public function addOrderInfo()
*public function orderList()
*public function orderListUpdate()
*public function orderListComplete()
*public function items()
*public function itemlist()
*public function eventDeleteProduct($product_id)
*public function eventEditProduct()
*public function purge()
#### 
#### extension\payment.php #class ControllerExtensionPayment extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*public function getList()
*protected function validate()
#### 
#### extension\shipping.php #class ControllerExtensionShipping extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*public function getList()
*protected function validate()
#### 
#### extension\total.php #class ControllerExtensionTotal extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*public function getList()
*protected function validate()
#### 
#### feed\google_base.php #class ControllerFeedGoogleBase extends Controller
*private $error
*public function index()
*protected function validate()
*public function install()
*public function uninstall()
*public function import()
*public function category()
*public function addCategory()
*public function removeCategory()
*public function autocomplete()
#### 
#### feed\google_sitemap.php #class ControllerFeedGoogleSitemap extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### feed\openbaypro.php #class ControllerFeedOpenbaypro extends Controller
*private $error
*public function index()
*protected function validate()
*public function install()
*public function uninstall()
#### 
#### fraud\fraudlabspro.php #class ControllerFraudFraudLabsPro extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*protected function validate()
*public function order()
*private function fix_case($s)
#### 
#### fraud\ip.php #class ControllerFraudIp extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*protected function validate()
*public function ip()
*public function addIp()
*public function removeIp()
#### 
#### fraud\maxmind.php #class ControllerFraudMaxMind extends Controller
*private $error
*public function index()
*public function install()
*public function uninstall()
*protected function validate()
*public function order()
#### 
#### localisation\country.php #class ControllerLocalisationCountry extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function country()
#### 
#### localisation\currency.php #class ControllerLocalisationCurrency extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*protected function validateRefresh()
#### 
#### localisation\geo_zone.php #class ControllerLocalisationGeoZone extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function zone()
#### 
#### localisation\language.php #class ControllerLocalisationLanguage extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\length_class.php #class ControllerLocalisationLengthClass extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\location.php #class ControllerLocalisationLocation extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\order_status.php #class ControllerLocalisationOrderStatus extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\return_action.php #class ControllerLocalisationReturnAction extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\return_reason.php #class ControllerLocalisationReturnReason extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\return_status.php #class ControllerLocalisationReturnStatus extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\stock_status.php #class ControllerLocalisationStockStatus extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\tax_class.php #class ControllerLocalisationTaxClass extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\tax_rate.php #class ControllerLocalisationTaxRate extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\weight_class.php #class ControllerLocalisationWeightClass extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### localisation\zone.php #class ControllerLocalisationZone extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### marketing\affiliate.php #class ControllerMarketingAffiliate extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function approve()
*public function unlock()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*protected function validateApprove()
*protected function validateUnlock()
*public function transaction()
*public function addTransaction()
*public function autocomplete()
#### 
#### marketing\contact.php #class ControllerMarketingContact extends Controller
*private $error
*public function index()
*public function send()
#### 
#### marketing\coupon.php #class ControllerMarketingCoupon extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
*public function history()
#### 
#### marketing\marketing.php #class ControllerMarketingMarketing extends Controller
*private $error
*public function index()
*public function add()
*public function edit()
*public function delete()
*public function refresh()
*protected function getList()
*protected function getForm()
*protected function validateForm()
*protected function validateDelete()
#### 
#### module\account.php #class ControllerModuleAccount extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\affiliate.php #class ControllerModuleAffiliate extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\amazon_login.php #class ControllerModuleAmazonLogin extends Controller
*private $error
*public function index()
*protected function validate()
*public function install()
*public function uninstall()
#### 
#### module\amazon_pay.php #class ControllerModuleAmazonPay extends Controller
*private $error
*public function index()
*protected function validate()
*public function install()
*public function uninstall()
#### 
#### module\banner.php #class ControllerModuleBanner extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\bestseller.php #class ControllerModuleBestSeller extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\carousel.php #class ControllerModuleCarousel extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\category.php #class ControllerModuleCategory extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\ebay_listing.php #class ControllerModuleEbayListing extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\featured.php #class ControllerModuleFeatured extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\filter.php #class ControllerModulefilter extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\google_hangouts.php #class ControllerModuleGoogleHangouts extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\html.php #class ControllerModuleHTML extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\information.php #class ControllerModuleInformation extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\latest.php #class ControllerModuleLatest extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\pp_button.php #class ControllerModulePPButton extends Controller
*public function index()
*protected function validate()
#### 
#### module\pp_login.php #class ControllerModulePPLogin extends Controller
*private $error
*public function index()
*protected function validate()
*public function install()
*public function uninstall()
#### 
#### module\slideshow.php #class ControllerModuleSlideshow extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\special.php #class ControllerModuleSpecial extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### module\store.php #class ControllerModuleStore extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### openbay\amazon.php #class ControllerOpenbayAmazon extends Controller
*public function install()
*public function uninstall()
*public function index()
*public function stockUpdates()
*public function subscription()
*public function settings()
*public function itemLinks()
*public function savedListings()
*protected function validate()
*public function getVariants()
*public function addLink()
*public function deleteLink()
*public function getLinks()
*public function getUnlinked()
*public function doBulkList()
*public function doBulkSearch()
*public function bulkListProducts()
*public function bulkLinking()
*public function loadListingReport()
*public function doBulkLinking()
*public function doFullStockSync()
#### 
#### openbay\amazonus.php #class ControllerOpenbayAmazonus extends Controller
*public function install()
*public function uninstall()
*public function index()
*public function stockUpdates()
*public function subscription()
*public function settings()
*public function itemLinks()
*public function savedListings()
*protected function validate()
*public function getVariants()
*public function addLink()
*public function deleteLink()
*public function getLinks()
*public function getUnlinked()
*public function doBulkList()
*public function doBulkSearch()
*public function bulkListProducts()
*public function bulkLinking()
*public function loadListingReport()
*public function doBulkLinking()
*public function doFullStockSync()
#### 
#### openbay\amazonus_listing.php #class ControllerOpenbayAmazonusListing extends Controller
*public function create()
*public function edit()
*public function createNew()
*public function deleteLinks()
*public function search()
*public function bestPrice()
*public function getProductByAsin()
*public function getBrowseNodes()
#### 
#### openbay\amazonus_product.php #class ControllerOpenbayAmazonusProduct extends Controller
*public function index()
*public function removeErrors()
*public function deleteSaved()
*public function uploadSaved()
*private function uploadItems()
*public function parseTemplateAjax()
*private function fillDefaultValues($product_id, $fields_array, $var = '')
*private function fillSavedValues($product_id, $fields_array, $var = '')
*public function resetPending()
*private function validateForm()
*private function formatUrlsInText($text)
#### 
#### openbay\amazon_listing.php #class ControllerOpenbayAmazonListing extends Controller
*public function create()
*public function edit()
*public function createNew()
*public function deleteLinks()
*public function search()
*public function bestPrice()
*public function getProductByAsin()
*public function getBrowseNodes()
#### 
#### openbay\amazon_product.php #class ControllerOpenbayAmazonProduct extends Controller
*public function index()
*public function removeErrors()
*public function deleteSaved()
*public function uploadSaved()
*private function uploadItems()
*public function parseTemplateAjax()
*private function fillDefaultValues($product_id, $fields_array, $var = '')
*private function fillSavedValues($product_id, $fields_array, $var = '')
*public function resetPending()
*private function validateForm()
*private function formatUrlsInText($text)
#### 
#### openbay\ebay.php #class ControllerOpenbayEbay extends Controller
*public function install()
*public function uninstall()
*public function index()
*public function settings()
*public function updateSettings()
*public function updateCategories()
*public function updateStore()
*public function getCategories()
*public function getSuggestedCategories()
*public function getShippingService()
*public function getEbayCategorySpecifics()
*public function getCategoryFeatures()
*public function searchEbayCatalog()
*public function summary()
*public function getSellerSummary()
*public function verifyCredentials()
*public function viewItemImport()
*public function importItems()
*public function getImportImages()
*public function importOrdersManual()
*public function getProductStock()
*public function setProductStock()
*public function getPlans()
*public function getMyPlan()
*public function subscription()
*public function viewUsage()
*public function getUsage()
*public function viewOrderImport()
*public function syncronise()
*public function viewItemLinks()
*public function saveItemLink()
*public function removeItemLink()
*public function loadUnlinked()
*public function loadLinkedStatus()
*private function validate()
*private function checkConfig()
*public function edit()
*public function editLoad()
*public function editSave()
*public function create()
*public function createBulk()
*public function verify()
*public function verifyBulk()
*public function listItem()
*public function listItemBulk()
*public function repairLinks()
*public function deleteAllLocks()
*public function endItem()
*public function getPartsCompatibilityOptions()
*public function getPartsCompatibilityValues()
*public function getItemRecommendations()
#### 
#### openbay\ebay_profile.php #class ControllerOpenbayEbayProfile extends Controller
*private $error
*public function profileAll()
*public function add()
*public function delete()
*public function edit()
*public function profileForm($data)
*public function profileGet()
*private function profileValidate()
#### 
#### openbay\ebay_template.php #class ControllerOpenbayEbayTemplate extends Controller
*private $error
*public function listAll()
*public function add()
*public function delete()
*public function edit()
*public function templateForm($data)
*private function templateValidate()
#### 
#### openbay\etsy.php #class ControllerOpenbayEtsy extends Controller
*public function install()
*public function uninstall()
*public function index()
*public function settings()
*public function settingsUpdate()
*public function getOrders()
*protected function validate()
#### 
#### openbay\etsy_product.php #class ControllerOpenbayEtsyProduct extends Controller
*private $error
*public function create()
*public function createSubmit()
*public function edit()
*public function editSubmit()
*public function addImage()
*public function getCategory()
*public function getSubCategory()
*public function getSubSubCategory()
*public function addLink()
*public function deleteLink()
*public function links()
*public function listings()
*public function endListing()
*public function deactivateListing()
*public function activateListing()
#### 
#### openbay\etsy_shipping.php #class ControllerOpenbayEtsyShipping extends Controller
*public function getAll()
#### 
#### openbay\etsy_shop.php #class ControllerOpenbayEtsyShop extends Controller
*public function getSections()
#### 
#### payment\amazon_login_pay.php #class ControllerPaymentAmazonLoginPay extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function cancel() {
*public function capture() {
*public function refund() {
*protected function validate() {
#### 
#### payment\authorizenet_aim.php #class ControllerPaymentAuthorizenetAim extends Controller
*private $error
*public function index() {
*protected function validate() {
#### 
#### payment\authorizenet_sim.php #class ControllerPaymentAuthorizeNetSim extends Controller
*private $error
*public function index() {
*protected function validate() {
#### 
#### payment\bank_transfer.php #class ControllerPaymentBankTransfer extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\bluepay_hosted.php #class ControllerPaymentBluePayHosted extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function void() {
*public function release() {
*public function rebate() {
*protected function validate() {
*public function callback() {
#### 
#### payment\bluepay_redirect.php #class ControllerPaymentBluepayredirect extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function void() {
*public function release() {
*public function rebate() {
*protected function validate() {
*public function callback() {
#### 
#### payment\cheque.php #class ControllerPaymentCheque extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\cod.php #class ControllerPaymentCod extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\firstdata.php #class ControllerPaymentFirstdata extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function void() {
*public function capture() {
*protected function validate() {
#### 
#### payment\firstdata_remote.php #class ControllerPaymentFirstdataRemote extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function void() {
*public function capture() {
*public function refund() {
*protected function validate() {
#### 
#### payment\free_checkout.php #class ControllerPaymentFreeCheckout extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\g2apay.php #class ControllerPaymentG2APay extends Controller
*private $error
*public function index() {
*public function order() {
*public function refund() {
*public function install() {
*public function uninstall() {
*protected function validate() {
#### 
#### payment\globalpay.php #class ControllerPaymentGlobalpay extends Controller
*private $error
*public function index() {
*public function install() {
*public function order() {
*public function void() {
*public function capture() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\globalpay_remote.php #class ControllerPaymentGlobalpayRemote extends Controller
*private $error
*public function index() {
*public function install() {
*public function order() {
*public function void() {
*public function capture() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\klarna_account.php #class ControllerPaymentKlarnaAccount extends Controller
*private $error
*private $pclasses
*public function index() {
*private function validate() {
*private function parseResponse($node, $document) {
*public function clear() {
#### 
#### payment\klarna_invoice.php #class ControllerPaymentKlarnaInvoice extends Controller
*private $error
*private $pclasses
*public function index() {
*private function validate() {
*private function parseResponse($node, $document) {
*public function clear() {
#### 
#### payment\liqpay.php #class ControllerPaymentLiqPay extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\nochex.php #class ControllerPaymentNOCHEX extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\paymate.php #class ControllerPaymentPayMate extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\paypoint.php #class ControllerPaymentPayPoint extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\payza.php #class ControllerPaymentPayza extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\perpetual_payments.php #class ControllerPaymentPerpetualPayments extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\pp_express.php #class ControllerPaymentPPExpress extends Controller
*private $error
*public function index() {
*public function imageLogo() {
*protected function validate() {
*public function live() {
*public function sandbox() {
*public function resend() {
*public function capture() {
*public function void() {
*public function refund() {
*public function doRefund() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function search() {
*public function doSearch() {
*public function viewTransaction() {
*private function formatRows($data) {
*public function recurringCancel() {
*public function recurringButtons() {
#### 
#### payment\pp_payflow.php #class ControllerPaymentPPPayflow extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\pp_payflow_iframe.php #class ControllerPaymentPPPayflowIframe extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function refund() {
*public function doRefund() {
*public function capture() {
*public function void() {
*public function order() {
*protected function validate() {
#### 
#### payment\pp_pro.php #class ControllerPaymentPPPro extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\pp_pro_iframe.php #class ControllerPaymentPPProIframe extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function refund() {
*public function doRefund() {
*public function reauthorise() {
*public function viewTransaction() {
*public function capture() {
*public function void() {
*public function order() {
*public function resend() {
*protected function validate() {
#### 
#### payment\pp_standard.php #class ControllerPaymentPPStandard extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\realex.php #class ControllerPaymentRealex extends Controller
*private $error
*public function index() {
*public function install() {
*public function order() {
*public function void() {
*public function capture() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\realex_remote.php #class ControllerPaymentRealexRemote extends Controller
*private $error
*public function index() {
*public function install() {
*public function order() {
*public function void() {
*public function capture() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\sagepay_direct.php #class ControllerPaymentSagepayDirect extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function void() {
*public function release() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\sagepay_server.php #class ControllerPaymentSagepayServer extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function void() {
*public function release() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\sagepay_us.php #class ControllerPaymentSagepayUS extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\securetrading_pp.php #class ControllerPaymentSecureTradingPp extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function void() {
*public function release() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\securetrading_ws.php #class ControllerPaymentSecureTradingWs extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function downloadTransactions() {
*public function showTransactions() {
*public function order() {
*public function void() {
*public function release() {
*public function rebate() {
*protected function validate() {
#### 
#### payment\skrill.php #class ControllerPaymentSkrill extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\twocheckout.php #class ControllerPaymentTwoCheckout extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\web_payment_software.php #class ControllerPaymentWebPaymentSoftware extends Controller
*private $error
*public function index()
*protected function validate()
#### 
#### payment\worldpay.php #class ControllerPaymentWorldpay extends Controller
*private $error
*public function index() {
*public function install() {
*public function uninstall() {
*public function order() {
*public function refund() {
*protected function validate() {
#### 
#### report\affiliate.php #class ControllerReportAffiliate extends Controller
*public function index()
#### 
#### report\affiliate_activity.php #class ControllerReportAffiliateActivity extends Controller
*public function index()
#### 
#### report\customer_activity.php #class ControllerReportCustomerActivity extends Controller
*public function index()
#### 
#### report\customer_credit.php #class ControllerReportCustomerCredit extends Controller
*public function index()
#### 
#### report\customer_online.php #class ControllerReportCustomerOnline extends Controller
*public function index()
#### 
#### report\customer_order.php #class ControllerReportCustomerOrder extends Controller
*public function index()
#### 
#### report\customer_reward.php #class ControllerReportCustomerReward extends Controller
*public function index()
#### 
#### report\marketing.php #class ControllerReportMarketing extends Controller
*public function index()
#### 
#### report\product_purchased.php #class ControllerReportProductPurchased extends Controller
*public function index()
#### 
#### report\product_viewed.php #class ControllerReportProductViewed extends Controller
*public function index()
*public function reset()
#### 
#### report\sale_coupon.php #class ControllerReportSaleCoupon extends Controller
*public function index()
#### 
#### report\sale_order.php #class ControllerReportSaleOrder extends Controller
*public function index()
#### 
#### report\sale_return.php #class ControllerReportSaleReturn extends Controller
*public function index()
#### 
#### report\sale_shipping.php #class ControllerReportSaleShipping extends Controller
*public function index()
#### 
#### report\sale_tax.php #class ControllerReportSaleTax extends Controller
*public function index()
#### 
#### sale\order.php #class ControllerSaleOrder extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*protected function getList() {
*public function getForm() {
*public function info() {
*public function createInvoiceNo() {
*public function addReward() {
*public function removeReward() {
*public function addCommission() {
*public function removeCommission() {
*public function history() {
*public function invoice() {
*public function shipping() {
#### 
#### sale\recurring.php #class ControllerSaleRecurring extends Controller
*private $error
*public function index() {
*protected function getList() {
*public function info() {
#### 
#### sale\return.php #class ControllerSaleReturn extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*public function delete() {
*protected function getList() {
*protected function getForm() {
*protected function validateForm() {
*protected function validateDelete() {
*public function history() {
#### 
#### sale\voucher.php #class ControllerSaleVoucher extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*public function delete() {
*protected function getList() {
*protected function getForm() {
*protected function validateForm() {
*protected function validateDelete() {
*public function history() {
*public function send() {
#### 
#### sale\voucher_theme.php #class ControllerSaleVoucherTheme extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*public function delete() {
*protected function getList() {
*protected function getForm() {
*protected function validateForm() {
*protected function validateDelete() {
#### 
#### setting\setting.php #class ControllerSettingSetting extends Controller
*private $error
*public function index() {
*protected function validate() {
*public function template() {
#### 
#### setting\store.php #class ControllerSettingStore extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*public function delete() {
*protected function getList() {
*public function getForm() {
*protected function validateForm() {
*protected function validateDelete() {
*public function template() {
#### 
#### shipping\auspost.php #class ControllerShippingAusPost extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\citylink.php #class ControllerShippingCitylink extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\fedex.php #class ControllerShippingFedex extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\flat.php #class ControllerShippingFlat extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\free.php #class ControllerShippingFree extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\item.php #class ControllerShippingItem extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\parcelforce_48.php #class ControllerShippingParcelforce48 extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\pickup.php #class ControllerShippingPickup extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\royal_mail.php #class ControllerShippingRoyalMail extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\ups.php #class ControllerShippingUPS extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\usps.php #class ControllerShippingUsps extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### shipping\weight.php #class ControllerShippingWeight extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### tool\backup.php #class ControllerToolBackup extends Controller
*private $error
*public function index() {
*public function backup() {
#### 
#### tool\error_log.php #class ControllerToolErrorLog extends Controller
*private $error
*public function index() {
*public function download() {
*public function clear() {
#### 
#### tool\upload.php #class ControllerToolUpload extends Controller
*private $error
*public function index() {
*public function delete() {
*protected function getList() {
*protected function validateDelete() {
*public function download() {
*public function upload() {
#### 
#### total\coupon.php #class ControllerTotalCoupon extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\credit.php #class ControllerTotalCredit extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\handling.php #class ControllerTotalHandling extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\klarna_fee.php #class ControllerTotalKlarnaFee extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\low_order_fee.php #class ControllerTotalLowOrderFee extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\reward.php #class ControllerTotalReward extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\shipping.php #class ControllerTotalShipping extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\sub_total.php #class ControllerTotalSubTotal extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\tax.php #class ControllerTotalTax extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\total.php #class ControllerTotalTotal extends Controller
*private $error
*public function index() {
*protected function validate()
#### 
#### total\voucher.php #class ControllerTotalVoucher extends Controller
*private $error
*public function index() {
*protected function validate() {
*public function install() {
*public function uninstall() {
#### 
#### user\api.php #class ControllerUserApi extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*public function delete() {
*protected function getList() {
*protected function getForm() {
*protected function validateForm() {
*protected function validateDelete() {
*public function addIp() {
*public function deleteSession() {
#### 
#### user\user.php #class ControllerUserUser extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*public function delete() {
*protected function getList() {
*protected function getForm() {
*protected function validateForm() {
*protected function validateDelete() {
#### 
#### user\user_permission.php #class ControllerUserUserPermission extends Controller
*private $error
*public function index() {
*public function add() {
*public function edit() {
*public function delete() {
*protected function getList() {
*protected function getForm() {
*protected function validateForm() {
*protected function validateDelete() {
#### 
#### 
#### 
#### ### admin\model\
#### catalog\attribute.php #class ModelCatalogAttribute extends Model
*public function addAttribute($data)
*public function editAttribute($attribute_id, $data)
*public function deleteAttribute($attribute_id)
*public function getAttribute($attribute_id)
*public function getAttributes($data = array())
*public function getAttributeDescriptions($attribute_id)
*public function getAttributesByAttributeGroupId($data = array())
*public function getTotalAttributes()
*public function getTotalAttributesByAttributeGroupId($attribute_group_id)
#### 
#### catalog\attribute_group.php #class ModelCatalogAttributeGroup extends Model
*public function addAttributeGroup($data)
*public function editAttributeGroup($attribute_group_id, $data)
*public function deleteAttributeGroup($attribute_group_id)
*public function getAttributeGroup($attribute_group_id)
*public function getAttributeGroups($data = array())
*public function getAttributeGroupDescriptions($attribute_group_id)
*public function getTotalAttributeGroups()
#### 
#### catalog\category.php #class ModelCatalogCategory extends Model
*public function addCategory($data)
*public function editCategory($category_id, $data)
*public function deleteCategory($category_id)
*public function repairCategories($parent_id = 0)
*public function getCategory($category_id)
*public function getCategories($data = array())
*public function getCategoryDescriptions($category_id)
*public function getCategoryFilters($category_id)
*public function getCategoryStores($category_id)
*public function getCategoryLayouts($category_id)
*public function getTotalCategories()
*public function getTotalCategoriesByLayoutId($layout_id)
#### 
#### catalog\download.php #class ModelCatalogDownload extends Model
*public function addDownload($data)
*public function editDownload($download_id, $data)
*public function deleteDownload($download_id)
*public function getDownload($download_id)
*public function getDownloads($data = array())
*public function getDownloadDescriptions($download_id)
*public function getTotalDownloads()
#### 
#### catalog\filter.php #class ModelCatalogFilter extends Model
*public function addFilter($data)
*public function editFilter($filter_group_id, $data)
*public function deleteFilter($filter_group_id)
*public function getFilterGroup($filter_group_id)
*public function getFilterGroups($data = array())
*public function getFilterGroupDescriptions($filter_group_id)
*public function getFilter($filter_id)
*public function getFilters($data)
*public function getFilterDescriptions($filter_group_id)
*public function getTotalFilterGroups()
#### 
#### catalog\information.php #class ModelCatalogInformation extends Model
*public function addInformation($data)
*public function editInformation($information_id, $data)
*public function deleteInformation($information_id)
*public function getInformation($information_id)
*public function getInformations($data = array())
*public function getInformationDescriptions($information_id)
*public function getInformationStores($information_id)
*public function getInformationLayouts($information_id)
*public function getTotalInformations()
*public function getTotalInformationsByLayoutId($layout_id)
#### 
#### catalog\manufacturer.php #class ModelCatalogManufacturer extends Model
*public function addManufacturer($data)
*public function editManufacturer($manufacturer_id, $data)
*public function deleteManufacturer($manufacturer_id)
*public function getManufacturer($manufacturer_id)
*public function getManufacturers($data = array())
*public function getManufacturerStores($manufacturer_id)
*public function getTotalManufacturers()
#### 
#### catalog\option.php #class ModelCatalogOption extends Model
*public function addOption($data)
*public function editOption($option_id, $data)
*public function deleteOption($option_id)
*public function getOption($option_id)
*public function getOptions($data = array())
*public function getOptionDescriptions($option_id)
*public function getOptionValue($option_value_id)
*public function getOptionValues($option_id)
*public function getOptionValueDescriptions($option_id)
*public function getTotalOptions()
#### 
#### catalog\product.php #class ModelCatalogProduct extends Model
*public function addProduct($data)
*public function editProduct($product_id, $data)
*public function copyProduct($product_id)
*public function deleteProduct($product_id)
*public function getProduct($product_id)
*public function getProducts($data = array())
*public function getProductsByCategoryId($category_id)
*public function getProductDescriptions($product_id)
*public function getProductCategories($product_id)
*public function getProductFilters($product_id)
*public function getProductAttributes($product_id)
*public function getProductOptions($product_id)
*public function getProductOptionValue($product_id, $product_option_value_id)
*public function getProductImages($product_id)
*public function getProductDiscounts($product_id)
*public function getProductSpecials($product_id)
*public function getProductRewards($product_id)
*public function getProductDownloads($product_id)
*public function getProductStores($product_id)
*public function getProductLayouts($product_id)
*public function getProductRelated($product_id)
*public function getRecurrings($product_id)
*public function getTotalProducts($data = array())
*public function getTotalProductsByTaxClassId($tax_class_id)
*public function getTotalProductsByStockStatusId($stock_status_id)
*public function getTotalProductsByWeightClassId($weight_class_id)
*public function getTotalProductsByLengthClassId($length_class_id)
*public function getTotalProductsByDownloadId($download_id)
*public function getTotalProductsByManufacturerId($manufacturer_id)
*public function getTotalProductsByAttributeId($attribute_id)
*public function getTotalProductsByOptionId($option_id)
*public function getTotalProductsByProfileId($recurring_id)
*public function getTotalProductsByLayoutId($layout_id)
#### 
#### catalog\recurring.php #class ModelCatalogRecurring extends Model
*public function addRecurring($data)
*public function editRecurring($recurring_id, $data)
*public function copyRecurring($recurring_id)
*public function deleteRecurring($recurring_id)
*public function getRecurring($recurring_id)
*public function getRecurringDescription($recurring_id)
*public function getRecurrings($data = array())
*public function getTotalRecurrings()
#### 
#### catalog\review.php #class ModelCatalogReview extends Model
*public function addReview($data)
*public function editReview($review_id, $data)
*public function deleteReview($review_id)
*public function getReview($review_id)
*public function getReviews($data = array())
*public function getTotalReviews($data = array())
*public function getTotalReviewsAwaitingApproval()
#### 
#### catalog\url_alias.php #class ModelCatalogUrlAlias extends Model
*public function getUrlAlias($keyword)
#### 
#### customer\customer.php #class ModelCustomerCustomer extends Model
*public function addCustomer($data)
*public function editCustomer($customer_id, $data)
*public function editToken($customer_id, $token)
*public function deleteCustomer($customer_id)
*public function getCustomer($customer_id)
*public function getCustomerByEmail($email)
*public function getCustomers($data = array())
*public function approve($customer_id)
*public function getAddress($address_id)
*public function getAddresses($customer_id)
*public function getTotalCustomers($data = array())
*public function getTotalCustomersAwaitingApproval()
*public function getTotalAddressesByCustomerId($customer_id)
*public function getTotalAddressesByCountryId($country_id)
*public function getTotalAddressesByZoneId($zone_id)
*public function getTotalCustomersByCustomerGroupId($customer_group_id)
*public function addHistory($customer_id, $comment)
*public function getHistories($customer_id, $start = 0, $limit = 10)
*public function getTotalHistories($customer_id)
*public function addTransaction($customer_id, $description = '', $amount = '', $order_id = 0)
*public function deleteTransaction($order_id)
*public function getTransactions($customer_id, $start = 0, $limit = 10)
*public function getTotalTransactions($customer_id)
*public function getTransactionTotal($customer_id)
*public function getTotalTransactionsByOrderId($order_id)
*public function addReward($customer_id, $description = '', $points = '', $order_id = 0)
*public function deleteReward($order_id)
*public function getRewards($customer_id, $start = 0, $limit = 10)
*public function getTotalRewards($customer_id)
*public function getRewardTotal($customer_id)
*public function getTotalCustomerRewardsByOrderId($order_id)
*public function getIps($customer_id, $start = 0, $limit = 10)
*public function getTotalIps($customer_id)
*public function getTotalCustomersByIp($ip)
*public function getTotalLoginAttempts($email)
*public function deleteLoginAttempts($email)
#### 
#### customer\customer_group.php #class ModelCustomerCustomerGroup extends Model
*public function addCustomerGroup($data)
*public function editCustomerGroup($customer_group_id, $data)
*public function deleteCustomerGroup($customer_group_id)
*public function getCustomerGroup($customer_group_id)
*public function getCustomerGroups($data = array())
*public function getCustomerGroupDescriptions($customer_group_id)
*public function getTotalCustomerGroups()
#### 
#### customer\custom_field.php #class ModelCustomerCustomField extends Model
*public function addCustomField($data)
*public function editCustomField($custom_field_id, $data)
*public function deleteCustomField($custom_field_id)
*public function getCustomField($custom_field_id)
*public function getCustomFields($data = array())
*public function getCustomFieldDescriptions($custom_field_id)
*public function getCustomFieldValue($custom_field_value_id)
*public function getCustomFieldValues($custom_field_id)
*public function getCustomFieldCustomerGroups($custom_field_id)
*public function getCustomFieldValueDescriptions($custom_field_id)
*public function getTotalCustomFields()
#### 
#### design\banner.php #class ModelDesignBanner extends Model
*public function addBanner($data)
*public function editBanner($banner_id, $data)
*public function deleteBanner($banner_id)
*public function getBanner($banner_id)
*public function getBanners($data = array())
*public function getBannerImages($banner_id)
*public function getTotalBanners()
#### 
#### design\layout.php #class ModelDesignLayout extends Model
*public function addLayout($data)
*public function editLayout($layout_id, $data)
*public function deleteLayout($layout_id)
*public function getLayout($layout_id)
*public function getLayouts($data = array())
*public function getLayoutRoutes($layout_id)
*public function getLayoutModules($layout_id)
*public function getTotalLayouts()
#### 
#### extension\event.php #class ModelExtensionEvent extends Model
*public function addEvent($code, $trigger, $action)
*public function deleteEvent($code)
#### 
#### extension\extension.php #class ModelExtensionExtension extends Model
*public function getInstalled($type)
*public function install($type, $code)
*public function uninstall($type, $code)
#### 
#### extension\modification.php #class ModelExtensionModification extends Model
*public function addModification($data)
*public function deleteModification($modification_id)
*public function enableModification($modification_id)
*public function disableModification($modification_id)
*public function getModification($modification_id)
*public function getModifications($data = array())
*public function getTotalModifications()
*public function getModificationByCode($code)
#### 
#### extension\module.php #class ModelExtensionModule extends Model
*public function addModule($code, $data)
*public function editModule($module_id, $data)
*public function deleteModule($module_id)
*public function getModule($module_id)
*public function getModules()
*public function getModulesByCode($code)
*public function deleteModulesByCode($code)
#### 
#### feed\google_base.php #class ModelFeedGoogleBase extends Model
*public function install()
*public function uninstall()
*public function import($string)
*public function getGoogleBaseCategories($data = array())
*public function addCategory($data)
*public function deleteCategory($category_id)
*public function getCategories($data = array())
*public function getTotalCategories()
#### 
#### fraud\fraudlabspro.php #class ModelFraudFraudLabsPro extends Model
*public function install()
*public function uninstall()
*public function getOrder($order_id)
*public function addOrderHistory($order_id, $data, $store_id = 0)
#### 
#### fraud\ip.php #class ModelFraudIp extends Model
*public function install()
*public function uninstall()
*public function addIp($ip)
*public function removeIp($ip)
*public function getIps($start = 0, $limit = 10)
*public function getTotalIps()
*public function getTotalIpsByIp($ip)
#### 
#### fraud\maxmind.php #class ModelFraudMaxMind extends Model
*public function install()
*public function uninstall()
*public function getOrder($order_id)
#### 
#### localisation\country.php #class ModelLocalisationCountry extends Model
*public function addCountry($data)
*public function editCountry($country_id, $data)
*public function deleteCountry($country_id)
*public function getCountry($country_id)
*public function getCountries($data = array())
*public function getTotalCountries()
#### 
#### localisation\currency.php #class ModelLocalisationCurrency extends Model
*public function addCurrency($data)
*public function editCurrency($currency_id, $data)
*public function deleteCurrency($currency_id)
*public function getCurrency($currency_id)
*public function getCurrencyByCode($currency)
*public function getCurrencies($data = array())
*public function refresh($force = false)
*public function getTotalCurrencies()
#### 
#### localisation\geo_zone.php #class ModelLocalisationGeoZone extends Model
*public function addGeoZone($data)
*public function editGeoZone($geo_zone_id, $data)
*public function deleteGeoZone($geo_zone_id)
*public function getGeoZone($geo_zone_id)
*public function getGeoZones($data = array())
*public function getTotalGeoZones()
*public function getZoneToGeoZones($geo_zone_id)
*public function getTotalZoneToGeoZoneByGeoZoneId($geo_zone_id)
*public function getTotalZoneToGeoZoneByCountryId($country_id)
*public function getTotalZoneToGeoZoneByZoneId($zone_id)
#### 
#### localisation\language.php #class ModelLocalisationLanguage extends Model
*public function addLanguage($data)
*public function editLanguage($language_id, $data)
*public function deleteLanguage($language_id)
*public function getLanguage($language_id)
*public function getLanguages($data = array())
*public function getTotalLanguages()
#### 
#### localisation\length_class.php #class ModelLocalisationLengthClass extends Model
*public function addLengthClass($data)
*public function editLengthClass($length_class_id, $data)
*public function deleteLengthClass($length_class_id)
*public function getLengthClasses($data = array())
*public function getLengthClass($length_class_id)
*public function getLengthClassDescriptionByUnit($unit)
*public function getLengthClassDescriptions($length_class_id)
*public function getTotalLengthClasses()
#### 
#### localisation\location.php #class ModelLocalisationLocation extends Model
*public function addLocation($data)
*public function editLocation($location_id, $data)
*public function deleteLocation($location_id)
*public function getLocation($location_id)
*public function getLocations($data = array())
*public function getTotalLocations()
#### 
#### localisation\order_status.php #class ModelLocalisationOrderStatus extends Model
*public function addOrderStatus($data)
*public function editOrderStatus($order_status_id, $data)
*public function deleteOrderStatus($order_status_id)
*public function getOrderStatus($order_status_id)
*public function getOrderStatuses($data = array())
*public function getOrderStatusDescriptions($order_status_id)
*public function getTotalOrderStatuses()
#### 
#### localisation\return_action.php #class ModelLocalisationReturnAction extends Model
*public function addReturnAction($data)
*public function editReturnAction($return_action_id, $data)
*public function deleteReturnAction($return_action_id)
*public function getReturnAction($return_action_id)
*public function getReturnActions($data = array())
*public function getReturnActionDescriptions($return_action_id)
*public function getTotalReturnActions()
#### 
#### localisation\return_reason.php #class ModelLocalisationReturnReason extends Model
*public function addReturnReason($data)
*public function editReturnReason($return_reason_id, $data)
*public function deleteReturnReason($return_reason_id)
*public function getReturnReason($return_reason_id)
*public function getReturnReasons($data = array())
*public function getReturnReasonDescriptions($return_reason_id)
*public function getTotalReturnReasons()
#### 
#### localisation\return_status.php #class ModelLocalisationReturnStatus extends Model
*public function addReturnStatus($data)
*public function editReturnStatus($return_status_id, $data)
*public function deleteReturnStatus($return_status_id)
*public function getReturnStatus($return_status_id)
*public function getReturnStatuses($data = array())
*public function getReturnStatusDescriptions($return_status_id)
*public function getTotalReturnStatuses()
#### 
#### localisation\stock_status.php #class ModelLocalisationStockStatus extends Model
*public function addStockStatus($data)
*public function editStockStatus($stock_status_id, $data)
*public function deleteStockStatus($stock_status_id)
*public function getStockStatus($stock_status_id)
*public function getStockStatuses($data = array())
*public function getStockStatusDescriptions($stock_status_id)
*public function getTotalStockStatuses()
#### 
#### localisation\tax_class.php #class ModelLocalisationTaxClass extends Model
*public function addTaxClass($data)
*public function editTaxClass($tax_class_id, $data)
*public function deleteTaxClass($tax_class_id)
*public function getTaxClass($tax_class_id)
*public function getTaxClasses($data = array())
*public function getTotalTaxClasses()
*public function getTaxRules($tax_class_id)
*public function getTotalTaxRulesByTaxRateId($tax_rate_id)
#### 
#### localisation\tax_rate.php #class ModelLocalisationTaxRate extends Model
*public function addTaxRate($data)
*public function editTaxRate($tax_rate_id, $data)
*public function deleteTaxRate($tax_rate_id)
*public function getTaxRate($tax_rate_id)
*public function getTaxRates($data = array())
*public function getTaxRateCustomerGroups($tax_rate_id)
*public function getTotalTaxRates()
*public function getTotalTaxRatesByGeoZoneId($geo_zone_id)
#### 
#### localisation\weight_class.php #class ModelLocalisationWeightClass extends Model
*public function addWeightClass($data)
*public function editWeightClass($weight_class_id, $data)
*public function deleteWeightClass($weight_class_id)
*public function getWeightClasses($data = array())
*public function getWeightClass($weight_class_id)
*public function getWeightClassDescriptionByUnit($unit)
*public function getWeightClassDescriptions($weight_class_id)
*public function getTotalWeightClasses()
#### 
#### localisation\zone.php #class ModelLocalisationZone extends Model
*public function addZone($data)
*public function editZone($zone_id, $data)
*public function deleteZone($zone_id)
*public function getZone($zone_id)
*public function getZones($data = array())
*public function getZonesByCountryId($country_id)
*public function getTotalZones()
*public function getTotalZonesByCountryId($country_id)
#### 
#### marketing\affiliate.php #class ModelMarketingAffiliate extends Model
*public function addAffiliate($data)
*public function editAffiliate($affiliate_id, $data)
*public function deleteAffiliate($affiliate_id)
*public function getAffiliate($affiliate_id)
*public function getAffiliateByEmail($email)
*public function getAffiliates($data = array())
*public function approve($affiliate_id)
*public function getAffiliatesByNewsletter()
*public function getTotalAffiliates($data = array())
*public function getTotalAffiliatesAwaitingApproval()
*public function getTotalAffiliatesByCountryId($country_id)
*public function getTotalAffiliatesByZoneId($zone_id)
*public function addTransaction($affiliate_id, $description = '', $amount = '', $order_id = 0)
*public function deleteTransaction($order_id)
*public function getTransactions($affiliate_id, $start = 0, $limit = 10)
*public function getTotalTransactions($affiliate_id)
*public function getTransactionTotal($affiliate_id)
*public function getTotalTransactionsByOrderId($order_id)
*public function getTotalLoginAttempts($email)
*public function deleteLoginAttempts($email)
#### 
#### marketing\coupon.php #class ModelMarketingCoupon extends Model
*public function addCoupon($data)
*public function editCoupon($coupon_id, $data)
*public function deleteCoupon($coupon_id)
*public function getCoupon($coupon_id)
*public function getCouponByCode($code)
*public function getCoupons($data = array())
*public function getCouponProducts($coupon_id)
*public function getCouponCategories($coupon_id)
*public function getTotalCoupons()
*public function getCouponHistories($coupon_id, $start = 0, $limit = 10)
*public function getTotalCouponHistories($coupon_id)
#### 
#### marketing\marketing.php #class ModelMarketingMarketing extends Model
*public function addMarketing($data)
*public function editMarketing($marketing_id, $data)
*public function deleteMarketing($marketing_id)
*public function getMarketing($marketing_id)
*public function getMarketings($data = array())
*public function getTotalMarketings($data = array())
#### 
#### openbay\amazon.php #class ModelOpenbayAmazon extends Model
*public function install()
*public function uninstall()
*public function patch()
*public function scheduleOrders($data)
*public function saveProduct($product_id, $data_array)
*public function deleteSaved($product_id, $var = '')
*public function getSavedProducts()
*public function getSavedProductsData()
*public function getProduct($product_id, $var = '')
*public function getProductCategory($product_id, $var = '')
*public function setProductUploaded($product_id, $insertion_id, $var = '')
*public function resetUploaded($insertion_id)
*public function getProductStatus($product_id)
*public function getProductErrors($product_id, $version = 2)
*public function getProductsWithErrors()
*public function deleteProduct($product_id)
*public function linkProduct($amazon_sku, $product_id, $var = '')
*public function removeProductLink($amazon_sku)
*public function removeAdvancedErrors($product_id)
*public function getProductLinks($product_id = 'all')
*public function getUnlinkedProducts()
*private function productLinkExists($product_id, $var)
*public function getOrderStatusString($order_id)
*public function updateAmazonOrderTracking($order_id, $courier_id, $courier_from_list, $tracking_no)
*public function getAmazonOrderId($order_id)
*public function getAmazonOrderedProducts($order_id)
*public function getProductQuantity($product_id, $var = '')
*public function getProductSearchTotal($data = array())
*public function getProductSearch($data = array())
*public function updateAmazonSkusQuantities($skus)
*public function deleteListingReports($marketplace)
*public function getTotalUnlinkedItemsFromReport($marketplace)
*public function getUnlinkedItemsFromReport($marketplace, $limit = 100, $page = 1)
*public function getAsinLink($asin, $marketplace)
#### 
#### openbay\amazonus.php #class ModelOpenbayAmazonus extends Model
*public function install()
*public function uninstall()
*public function patch()
*public function scheduleOrders($data)
*public function saveProduct($product_id, $data_array)
*public function deleteSaved($product_id, $var = '')
*public function getSavedProducts()
*public function getSavedProductsData()
*public function getProduct($product_id, $var = '')
*public function getProductCategory($product_id, $var = '')
*public function setProductUploaded($product_id, $insertion_id, $var = '')
*public function resetUploaded($insertion_id)
*public function getProductStatus($product_id)
*public function getProductErrors($product_id, $version = 2)
*public function getProductsWithErrors()
*public function deleteProduct($product_id)
*public function linkProduct($amazonus_sku, $product_id, $var = '')
*public function removeProductLink($amazonus_sku)
*public function removeAdvancedErrors($product_id)
*public function getProductLinks($product_id = 'all')
*public function getUnlinkedProducts()
*private function productLinkExists($product_id, $var)
*public function getOrderStatusString($order_id)
*public function updateAmazonusOrderTracking($order_id, $courier_id, $courier_from_list, $tracking_no)
*public function getAmazonusOrderId($order_id)
*public function getAmazonusOrderedProducts($order_id)
*public function getProductQuantity($product_id, $var = '')
*public function getProductSearchTotal($data = array())
*public function getProductSearch($data = array())
*public function updateAmazonSkusQuantities($skus)
*public function getTotalUnlinkedItemsFromReport()
*public function getUnlinkedItemsFromReport($limit = 100, $page = 1)
*public function deleteListingReports()
#### 
#### openbay\amazonus_listing.php #class ModelOpenbayAmazonusListing extends Model
*private $tabs
*public function search($search_string)
*public function getProductByAsin($asin)
*public function getBestPrice($asin, $condition)
*public function simpleListing($data)
*public function getBrowseNodes($request)
*public function deleteSearchResults($product_ids)
*public function doBulkListing($data)
*public function doBulkSearch($search_data)
#### 
#### openbay\amazon_listing.php #class ModelOpenbayAmazonListing extends Model
*private $tabs
*public function search($search_string, $marketplace)
*public function getProductByAsin($asin, $market)
*public function getBestPrice($asin, $condition, $marketplace)
*public function simpleListing($data)
*public function getBrowseNodes($request)
*public function doBulkSearch($search_data)
*public function deleteSearchResults($marketplace, $product_ids)
*public function doBulkListing($data)
#### 
#### openbay\ebay.php #class ModelOpenbayEbay extends Model{
*public function install()
*public function uninstall()
*public function patch()
*public function totalLinked()
*public function loadLinked($limit = 100, $page = 1)
*public function loadLinkedStatus($item_ids)
*public function loadUnlinked($limit = 200, $page = 1, $filter = array())
*public function loadItemLinks()
*public function saveItemLink($data)
*public function getSellerStoreCategories()
*public function getCategory($parent)
*public function getSuggestedCategories($qry)
*public function getShippingService($international, $type)
*public function getShippingLocations()
*public function getEbayCategorySpecifics($category_id)
*public function getCategoryFeatures($category_id)
*public function getSellerSummary()
*public function getPaymentTypes()
*public function getPopularCategories()
*private function getCategoryStructure($id)
*public function ebayVerifyAddItem($data, $options)
*public function ebayAddItem($data, $options)
*public function logCategoryUsed($category_id)
*public function getProductStock($id)
*public function getUsage()
*public function getPlans()
*public function getMyPlan()
*public function getLiveListingArray()
*public function verifyCredentials()
*public function editSave($data)
*public function getProductAttributes($product_id)
#### 
#### openbay\ebay_product.php #class ModelOpenbayEbayProduct extends Model
*public function getTaxRate($class_id)
*public function countImportImages()
*public function getProductOptions($product_id)
*public function repairLinks()
*public function searchEbayCatalog($search, $category_id, $page = 1)
*public function getPartsCompatibilityOptions($category_id)
*public function getPartsCompatibilityValues($filters)
*public function getItemRecommendations($filters)
#### 
#### openbay\ebay_profile.php #class ModelOpenbayEbayProfile extends Model{
*public function add($data)
*public function edit($id, $data)
*public function delete($id)
*public function get($id)
*public function getAll($type = '')
*public function getTypes()
*public function getDefault($type)
*private function clearDefault($type)
#### 
#### openbay\ebay_template.php #class ModelOpenbayEbayTemplate extends Model
*public function add($data)
*public function edit($id, $data)
*public function delete($id)
*public function get($id)
*public function getAll()
#### 
#### openbay\etsy.php #class ModelOpenbayEtsy extends Model{
*public function install()
*public function uninstall()
*public function patch()
*public function verifyAccount()
#### 
#### openbay\etsy_product.php #class ModelOpenbayEtsyProduct extends Model{
*public function getStatus($product_id)
*public function totalLinked()
*public function addLink($product_id, $etsy_item_id, $status_id = 0)
*public function loadLinked($limit = 100, $page = 1)
#### 
#### openbay\openbay.php #class ModelOpenbayOpenbay extends Model
*private $url = 'https://account.openbaypro.com/'
*private $error;
*public function patch()
*public function updateV2Test()
*public function updateV2CheckVersion($beta = 0)
*public function updateV2Download($beta = 0)
*public function updateV2Extract()
*public function updateV2Remove($beta = 0)
*public function updateV2UpdateVersion($beta = 0)
*public function setUrl($url)
*public function updateTest()
*public function update()
*public function getNotifications()
*public function version()
*public function faqGet($route)
*public function faqIsDismissed($route)
*public function faqDismiss($route)
*public function faqClear()
*public function faqDbTableCheck()
*private function ftpDir($file, $connection)
*public function requirementTest()
*private function call($call, array $post = null, array $options = array(), $content_type = 'json')
*public function writeUpdateLog($data)
*public function getTotalProducts($data = array())
*public function getProducts($data = array())
*public function addOrderHistory($order_id, $data, $store_id = 0)
#### 
#### openbay\order.php #class ModelOpenbayOrder extends Model
*public function getTotalOrders($data = array())
*public function getOrders($data = array())
*public function getOrder($order_id)
#### 
#### openbay\version.php #class ModelOpenbayVersion extends Model
*public function version()
#### 
#### payment\amazon_login_pay.php #class ModelPaymentAmazonLoginPay extends Model
*public function install()
*public function uninstall()
*public function getOrder($order_id)
*public function cancel($amazon_login_pay_order)
*public function updateCancelStatus($amazon_login_pay_order_id, $status)
*public function capture($amazon_login_pay_order, $amount)
*private function authorize($amazon_login_pay_order, $amount)
*public function closeOrderRef($amazon_order_reference_id)
*public function updateCaptureStatus($amazon_login_pay_order_id, $status)
*public function refund($amazon_login_pay_order, $amount)
*public function getUnCaptured($amazon_login_pay_order_id)
*public function updateRefundStatus($amazon_login_pay_order_id, $status)
*public function getCapturesRemaining($amazon_login_pay_order_id)
*private function getTransactions($amazon_login_pay_order_id, $currency_code)
*public function addTransaction($amazon_login_pay_order_id, $type, $status, $total, $amazon_authorization_id = null, $amazon_capture_id = null, $amazon_refund_id = null)
*public function getTotalCaptured($amazon_login_pay_order_id)
*public function getTotalRefunded($amazon_login_pay_order_id)
*public function validateDetails($data)
*public function offAmazon($Action, $parameter_data, $post_data = array())
*private function validateResponse($action, $details)
*public function sendCurl($url, $parameters)
*private function getParametersAsString(array $parameters)
*private function calculateStringToSignV2(array $parameters, $url)
*private function urlencode($value)
*public function logger($message)
#### 
#### payment\bluepay_hosted.php #class ModelPaymentBluePayHosted extends Model
*public function install()
*public function uninstall()
*public function void($order_id)
*public function updateVoidStatus($bluepay_hosted_order_id, $status)
*public function release($order_id, $amount)
*public function updateReleaseStatus($bluepay_hosted_order_id, $status)
*public function rebate($order_id, $amount)
*public function updateRebateStatus($bluepay_hosted_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($bluepay_hosted_order_id)
*public function addTransaction($bluepay_hosted_order_id, $type, $total)
*public function getTotalReleased($bluepay_hosted_order_id)
*public function getTotalRebated($bluepay_hosted_order_id)
*public function sendCurl($url, $post_data)
*public function adminCallback()
*public function logger($message)
#### 
#### payment\bluepay_redirect.php #class ModelPaymentBluepayredirect extends Model
*public function install()
*public function uninstall()
*public function void($order_id)
*public function updateVoidStatus($bluepay_redirect_order_id, $status)
*public function release($order_id, $amount)
*public function updateReleaseStatus($bluepay_redirect_order_id, $status)
*public function rebate($order_id, $amount)
*public function updateRebateStatus($bluepay_redirect_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($bluepay_redirect_order_id)
*public function addTransaction($bluepay_redirect_order_id, $type, $total)
*public function getTotalReleased($bluepay_redirect_order_id)
*public function getTotalRebated($bluepay_redirect_order_id)
*public function sendCurl($url, $post_data)
*public function callback()
*public function logger($message)
#### 
#### payment\firstdata.php #class ModelPaymentFirstdata extends Model
*public function install()
*public function uninstall()
*public function void($order_id)
*public function updateVoidStatus($firstdata_order_id, $status)
*public function capture($order_id, $amount)
*public function updateCaptureStatus($firstdata_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($firstdata_order_id)
*public function addTransaction($firstdata_order_id, $type, $total)
*public function logger($message)
*public function getTotalCaptured($firstdata_order_id)
*public function mapCurrency($code)
#### 
#### payment\firstdata_remote.php #class ModelPaymentFirstdataRemote extends Model
*public function install()
*public function uninstall()
*public function call($xml)
*public function void($order_ref, $tdate)
*public function updateVoidStatus($firstdata_remote_order_id, $status)
*public function capture($order_ref, $total, $currency_code)
*public function updateCaptureStatus($firstdata_remote_order_id, $status)
*public function refund($order_ref, $total, $currency_code)
*public function updateRefundStatus($firstdata_remote_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($firstdata_remote_order_id)
*public function addTransaction($firstdata_remote_order_id, $type, $total)
*public function logger($message)
*public function getTotalCaptured($firstdata_order_id)
*public function getTotalRefunded($firstdata_order_id)
*public function mapCurrency($code)
#### 
#### payment\g2apay.php #class ModelPaymentG2aPay extends Model
*public function install()
*public function uninstall()
*public function getOrder($order_id)
*public function getTotalReleased($g2apay_order_id)
*public function refund($g2apay_order, $amount)
*public function updateRefundStatus($g2apay_order_id, $status)
*private function getTransactions($g2apay_order_id, $currency_code)
*public function addTransaction($g2apay_order_id, $type, $total)
*public function getTotalRefunded($g2apay_order_id)
*public function sendCurl($url, $fields)
*public function logger($message)
#### 
#### payment\globalpay.php #class ModelPaymentGlobalpay extends Model
*public function install()
*public function void($order_id)
*public function updateVoidStatus($globalpay_order_id, $status)
*public function capture($order_id, $amount)
*public function updateCaptureStatus($globalpay_order_id, $status)
*public function updateForRebate($globalpay_order_id, $pas_ref, $order_ref)
*public function rebate($order_id, $amount)
*public function updateRebateStatus($globalpay_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($globalpay_order_id)
*public function addTransaction($globalpay_order_id, $type, $total)
*public function logger($message)
*public function getTotalCaptured($globalpay_order_id)
*public function getTotalRebated($globalpay_order_id)
#### 
#### payment\globalpay_remote.php #class ModelPaymentGlobalpayRemote extends Model
*public function install()
*public function void($order_id)
*public function updateVoidStatus($globalpay_remote_order_id, $status)
*public function capture($order_id, $amount)
*public function updateCaptureStatus($globalpay_remote_order_id, $status)
*public function updateForRebate($globalpay_remote_order_id, $pas_ref, $order_ref)
*public function rebate($order_id, $amount)
*public function updateRebateStatus($globalpay_remote_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($globalpay_remote_order_id)
*public function addTransaction($globalpay_remote_order_id, $type, $total)
*public function logger($message)
*public function getTotalCaptured($globalpay_order_id)
*public function getTotalRebated($globalpay_order_id)
#### 
#### payment\pp_express.php #class ModelPaymentPPExpress extends Model
*public function install()
*public function uninstall()
*public function totalCaptured($paypal_order_id)
*public function totalRefundedOrder($paypal_order_id)
*public function totalRefundedTransaction($transaction_id)
*public function log($data, $title = null)
*public function getOrder($order_id)
*public function updateOrder($capture_status, $order_id)
*public function addTransaction($transaction_data, $request_data = array())
*public function getFailedTransaction($paypal_order_transaction_id)
*public function updateTransaction($transaction)
*private function getTransactions($paypal_order_id)
*public function getLocalTransaction($transaction_id)
*public function getTransaction($transaction_id)
*public function cleanReturn($data)
*public function call($data)
*public function getOrderId($transaction_id)
*public function currencyCodes()
*public function recurringCancel($ref)
*public function getTokens($test)
*public function getUserInfo($merchant_id, $test, $access_token)
*private function curl($endpoint, $additional_opts = array())
#### 
#### payment\pp_payflow_iframe.php #class ModelPaymentPPPayflowIFrame extends Model
*public function install()
*public function uninstall()
*public function log($message)
*public function getOrder($order_id)
*public function updateOrderStatus($order_id, $status)
*public function addTransaction($data)
*public function getTransactions($order_id)
*public function getTransaction($transaction_reference)
*public function call($data)
#### 
#### payment\pp_pro_iframe.php #class ModelPaymentPPProIframe extends Model
*public function install()
*public function uninstall()
*private function getTransactions($paypal_iframe_order_id)
*public function totalCaptured($paypal_iframe_order_id)
*public function totalRefundedOrder($paypal_iframe_order_id)
*public function totalRefundedTransaction($transaction_id)
*public function getOrder($order_id)
*public function call($data)
*public function updateOrder($capture_status, $order_id)
*public function updateTransaction($transaction)
*public function addTransaction($transaction_data, $request_data = array())
*public function log($data, $title = null)
*public function getTransaction($transaction_id)
*public function getOrderId($transaction_id)
*public function updateAuthorizationId($paypal_iframe_order_id, $authorization_id)
*public function updateRefundTransaction($transaction_id, $transaction_type)
*public function getFailedTransaction($paypl_iframe_order_transaction_id)
*public function getLocalTransaction($transaction_id)
*protected function cleanReturn($data)
#### 
#### payment\realex.php #class ModelPaymentRealex extends Model
*public function install()
*public function void($order_id)
*public function updateVoidStatus($realex_order_id, $status)
*public function capture($order_id, $amount)
*public function updateCaptureStatus($realex_order_id, $status)
*public function updateForRebate($realex_order_id, $pas_ref, $order_ref)
*public function rebate($order_id, $amount)
*public function updateRebateStatus($realex_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($realex_order_id)
*public function addTransaction($realex_order_id, $type, $total)
*public function logger($message)
*public function getTotalCaptured($realex_order_id)
*public function getTotalRebated($realex_order_id)
#### 
#### payment\realex_remote.php #class ModelPaymentRealexRemote extends Model
*public function install()
*public function void($order_id)
*public function updateVoidStatus($realex_remote_order_id, $status)
*public function capture($order_id, $amount)
*public function updateCaptureStatus($realex_remote_order_id, $status)
*public function updateForRebate($realex_remote_order_id, $pas_ref, $order_ref)
*public function rebate($order_id, $amount)
*public function updateRebateStatus($realex_remote_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($realex_remote_order_id)
*public function addTransaction($realex_remote_order_id, $type, $total)
*public function logger($message)
*public function getTotalCaptured($realex_order_id)
*public function getTotalRebated($realex_order_id)
#### 
#### payment\sagepay_direct.php #class ModelPaymentSagepayDirect extends Model
*public function install()
*public function uninstall()
*public function void($order_id)
*public function updateVoidStatus($sagepay_direct_order_id, $status)
*public function release($order_id, $amount)
*public function updateReleaseStatus($sagepay_direct_order_id, $status)
*public function rebate($order_id, $amount)
*public function updateRebateStatus($sagepay_direct_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($sagepay_direct_order_id)
*public function addTransaction($sagepay_direct_order_id, $type, $total)
*public function getTotalReleased($sagepay_direct_order_id)
*public function getTotalRebated($sagepay_direct_order_id)
*public function sendCurl($url, $payment_data)
*public function logger($message)
#### 
#### payment\sagepay_server.php #class ModelPaymentSagepayServer extends Model
*public function install()
*public function uninstall()
*public function void($order_id)
*public function updateVoidStatus($sagepay_server_order_id, $status)
*public function release($order_id, $amount)
*public function updateReleaseStatus($sagepay_server_order_id, $status)
*public function updateForRebate($sagepay_server_order_id, $order_ref)
*public function rebate($order_id, $amount)
*public function getOrder($order_id)
*private function getTransactions($sagepay_server_order_id)
*public function addTransaction($sagepay_server_order_id, $type, $total)
*public function getTotalReleased($sagepay_server_order_id)
*public function getTotalRebated($sagepay_server_order_id)
*public function sendCurl($url, $payment_data)
*public function logger($message)
#### 
#### payment\securetrading_pp.php #class ModelPaymentSecureTradingPp extends Model
*public function install()
*public function uninstall()
*public function void($order_id)
*public function updateVoidStatus($securetrading_pp_order_id, $status)
*public function release($order_id, $amount)
*public function updateReleaseStatus($securetrading_pp_order_id, $status)
*public function updateForRebate($securetrading_pp_order_id, $order_ref)
*public function rebate($order_id, $refunded_amount)
*public function getOrder($order_id)
*private function getTransactions($securetrading_pp_order_id)
*public function addTransaction($securetrading_pp_order_id, $type, $total)
*public function getTotalReleased($securetrading_pp_order_id)
*public function getTotalRebated($securetrading_pp_order_id)
*public function increaseRefundedAmount($order_id, $amount)
*public function call($data)
*public function logger($message)
#### 
#### payment\securetrading_ws.php #class ModelPaymentSecureTradingWs extends Model
*public function install()
*public function uninstall()
*public function void($order_id)
*public function updateVoidStatus($securetrading_ws_order_id, $status)
*public function release($order_id, $amount)
*public function updateReleaseStatus($securetrading_ws_order_id, $status)
*public function updateForRebate($securetrading_ws_order_id, $order_ref)
*public function rebate($order_id, $refunded_amount)
*public function getOrder($order_id)
*private function getTransactions($securetrading_ws_order_id)
*public function addTransaction($securetrading_ws_order_id, $type, $total)
*public function getTotalReleased($securetrading_ws_order_id)
*public function getTotalRebated($securetrading_ws_order_id)
*public function increaseRefundedAmount($order_id, $amount)
*public function getCsv($data)
*private function encodePost($data)
*public function call($data)
*public function logger($message)
#### 
#### payment\worldpay.php #class ModelPaymentWorldpay extends Model
*public function install()
*public function uninstall()
*public function refund($order_id, $amount)
*public function updateRefundStatus($worldpay_order_id, $status)
*public function getOrder($order_id)
*private function getTransactions($worldpay_order_id, $currency_code)
*public function addTransaction($worldpay_order_id, $type, $total)
*public function getTotalReleased($worldpay_order_id)
*public function getTotalRefunded($worldpay_order_id)
*public function sendCurl($url, $order)
*public function logger($message)
#### 
#### report\activity.php #class ModelReportActivity extends Model
*public function getActivities()
#### 
#### report\affiliate.php #class ModelReportAffiliate extends Model
*public function getCommission($data = array())
*public function getTotalCommission($data = array())
*public function getProducts($data = array())
*public function getTotalProducts($data = array())
*public function getAffiliateActivities($data = array())
*public function getTotalAffiliateActivities($data = array())
#### 
#### report\coupon.php #class ModelReportCoupon extends Model
*public function getCoupons($data = array())
*public function getTotalCoupons($data = array())
#### 
#### report\customer.php #class ModelReportCustomer extends Model
*public function getTotalCustomersByDay()
*public function getTotalCustomersByWeek()
*public function getTotalCustomersByMonth()
*public function getTotalCustomersByYear()
*public function getOrders($data = array())
*public function getTotalOrders($data = array())
*public function getRewardPoints($data = array())
*public function getTotalRewardPoints($data = array())
*public function getCredit($data = array())
*public function getTotalCredit($data = array())
*public function getCustomersOnline($data = array())
*public function getTotalCustomersOnline($data = array())
*public function getCustomerActivities($data = array())
*public function getTotalCustomerActivities($data = array())
#### 
#### report\marketing.php #class ModelReportMarketing extends Model
*public function getMarketing($data = array())
*public function getTotalMarketing($data = array())
#### 
#### report\product.php #class ModelReportProduct extends Model
*public function getProductsViewed($data = array())
*public function getTotalProductViews()
*public function getTotalProductsViewed()
*public function reset()
*public function getPurchased($data = array())
*public function getTotalPurchased($data)
#### 
#### report\return.php #class ModelReportReturn extends Model
*public function getReturns($data = array())
*public function getTotalReturns($data = array())
#### 
#### report\sale.php #class ModelReportSale extends Model
*public function getTotalSales($data = array())
*public function getTotalOrdersByCountry()
*public function getTotalOrdersByDay()
*public function getTotalOrdersByWeek()
*public function getTotalOrdersByMonth()
*public function getTotalOrdersByYear()
*public function getOrders($data = array())
*public function getTotalOrders($data = array())
*public function getTaxes($data = array())
*public function getTotalTaxes($data = array())
*public function getShipping($data = array())
*public function getTotalShipping($data = array())
#### 
#### sale\order.php #class ModelSaleOrder extends Model
*public function getOrder($order_id)
*public function getOrders($data = array())
*public function getOrderProducts($order_id)
*public function getOrderOptions($order_id, $order_product_id)
*public function getOrderVouchers($order_id)
*public function getOrderVoucherByVoucherId($voucher_id)
*public function getOrderTotals($order_id)
*public function getTotalOrders($data = array())
*public function getTotalOrdersByStoreId($store_id)
*public function getTotalOrdersByOrderStatusId($order_status_id)
*public function getTotalOrdersByProcessingStatus()
*public function getTotalOrdersByCompleteStatus()
*public function getTotalOrdersByLanguageId($language_id)
*public function getTotalOrdersByCurrencyId($currency_id)
*public function createInvoiceNo($order_id)
*public function getOrderHistories($order_id, $start = 0, $limit = 10)
*public function getTotalOrderHistories($order_id)
*public function getTotalOrderHistoriesByOrderStatusId($order_status_id)
*public function getEmailsByProductsOrdered($products, $start, $end)
*public function getTotalEmailsByProductsOrdered($products)
#### 
#### sale\recurring.php #class ModelSaleRecurring extends Model
*public function getTotalRecurrings($data)
*public function getRecurrings($data)
*public function getRecurring($order_recurring_id)
*public function getRecurringTransactions($order_recurring_id)
*private function getStatus($status)
#### 
#### sale\return.php #class ModelSaleReturn extends Model
*public function addReturn($data)
*public function editReturn($return_id, $data)
*public function deleteReturn($return_id)
*public function getReturn($return_id)
*public function getReturns($data = array())
*public function getTotalReturns($data = array())
*public function getTotalReturnsByReturnStatusId($return_status_id)
*public function getTotalReturnsByReturnReasonId($return_reason_id)
*public function getTotalReturnsByReturnActionId($return_action_id)
*public function addReturnHistory($return_id, $data)
*public function getReturnHistories($return_id, $start = 0, $limit = 10)
*public function getTotalReturnHistories($return_id)
*public function getTotalReturnHistoriesByReturnStatusId($return_status_id)
#### 
#### sale\voucher.php #class ModelSaleVoucher extends Model
*public function addVoucher($data)
*public function editVoucher($voucher_id, $data)
*public function deleteVoucher($voucher_id)
*public function getVoucher($voucher_id)
*public function getVoucherByCode($code)
*public function getVouchers($data = array())
*public function sendVoucher($voucher_id)
*public function getTotalVouchers()
*public function getTotalVouchersByVoucherThemeId($voucher_theme_id)
*public function getVoucherHistories($voucher_id, $start = 0, $limit = 10)
*public function getTotalVoucherHistories($voucher_id)
#### 
#### sale\voucher_theme.php #class ModelSaleVoucherTheme extends Model
*public function addVoucherTheme($data)
*public function editVoucherTheme($voucher_theme_id, $data)
*public function deleteVoucherTheme($voucher_theme_id)
*public function getVoucherTheme($voucher_theme_id)
*public function getVoucherThemes($data = array())
*public function getVoucherThemeDescriptions($voucher_theme_id)
*public function getTotalVoucherThemes()
#### 
#### setting\setting.php #class ModelSettingSetting extends Model
*public function getSetting($code, $store_id = 0)
*public function editSetting($code, $data, $store_id = 0)
*public function deleteSetting($code, $store_id = 0)
*public function editSettingValue($code = '', $key = '', $value = '', $store_id = 0)
#### 
#### setting\store.php #class ModelSettingStore extends Model
*public function addStore($data)
*public function editStore($store_id, $data)
*public function deleteStore($store_id)
*public function getStore($store_id)
*public function getStores($data = array())
*public function getTotalStores()
*public function getTotalStoresByLayoutId($layout_id)
*public function getTotalStoresByLanguage($language)
*public function getTotalStoresByCurrency($currency)
*public function getTotalStoresByCountryId($country_id)
*public function getTotalStoresByZoneId($zone_id)
*public function getTotalStoresByCustomerGroupId($customer_group_id)
*public function getTotalStoresByInformationId($information_id)
*public function getTotalStoresByOrderStatusId($order_status_id)
#### 
#### tool\backup.php #class ModelToolBackup extends Model
*public function restore($sql)
*public function getTables()
*public function backup($tables)
#### 
#### tool\image.php #class ModelToolImage extends Model
*public function resize($filename, $width, $height)
#### 
#### tool\upload.php #class ModelToolUpload extends Model
*public function addUpload($name, $filename)
*public function deleteUpload($upload_id)
*public function getUpload($upload_id)
*public function getUploadByCode($code)
*public function getUploads($data = array())
*public function getTotalUploads()
#### 
#### user\api.php #class ModelUserApi extends Model
*public function addApi($data)
*public function editApi($api_id, $data)
*public function deleteApi($api_id)
*public function getApi($api_id)
*public function getApis($data = array())
*public function getTotalApis()
*public function addApiIp($api_id, $ip)
*public function getApiIps($api_id)
*public function getApiSessions($api_id)
*public function addApiSession($api_id, $data)
*public function deleteApiSession($api_session_id)
#### 
#### user\user.php #class ModelUserUser extends Model
*public function addUser($data)
*public function editUser($user_id, $data)
*public function editPassword($user_id, $password)
*public function editCode($email, $code)
*public function deleteUser($user_id)
*public function getUser($user_id)
*public function getUserByUsername($username)
*public function getUserByCode($code)
*public function getUsers($data = array())
*public function getTotalUsers()
*public function getTotalUsersByGroupId($user_group_id)
*public function getTotalUsersByEmail($email)
#### 
#### user\user_group.php #class ModelUserUserGroup extends Model
*public function addUserGroup($data)
*public function editUserGroup($user_group_id, $data)
*public function deleteUserGroup($user_group_id)
*public function getUserGroup($user_group_id)
*public function getUserGroups($data = array())
*public function getTotalUserGroups()
*public function addPermission($user_group_id, $type, $route)
*public function removePermission($user_group_id, $type, $route)



### install\
#### controller\footer.php #class ControllerFooter extends Controller
*public function index()
#### 
#### controller\header.php #class ControllerHeader extends Controller
*public function index()
#### 
#### controller\maxmind.php #class ControllerMaxmind extends Controller
*private $error
*public function index()
*private function validate()
#### 
#### controller\openbay.php #class ControllerOpenbay extends Controller
*public function index()
#### 
#### controller\step_1.php #class ControllerStep1 extends Controller
*public function index()
#### 
#### controller\step_2.php #class ControllerStep2 extends Controller
*private $error
*public function index()
*private function validate()
#### 
#### controller\step_3.php #class ControllerStep3 extends Controller
*private $error
*public function index()
*private function validate()
#### 
#### controller\step_4.php #class ControllerStep4 extends Controller
*public function index()
*public function extensions()
*public function language()
#### 
#### controller\upgrade.php #class ControllerUpgrade extends Controller
*private $error
*public function index()
*public function success()
*private function validate()
#### 
#### model\install.php #class ModelInstall extends Model
*public function database($data)
#### 
#### model\upgrade.php #class ModelUpgrade extends Model
*public function mysql()
*public function repairCategories($parent_id = 0)


### system\engine\
#### action.php #class Action
*private $file
*private $class
*private $method
*private $args
*public function __construct($route, $args = array())
*public function execute($registry)
#### 
#### controller.php #abstract class Controller
*protected $registry
*public function __construct($registry)
*public function __get($key)
*public function __set($key, $value)
#### 
#### event.php #class Event
*private $data
*private $registry
*public function __construct($registry)
*public function register($key, $action, $priority = 0)
*public function unregister($key, $action)
*public function trigger($key, &$arg = array())
*protected static function cmpByPriority($a, $b)
*protected function createAction($action, &$arg)
#### 
#### front.php #final class Front
*private $registry
*private $pre_action
*private $error
*public function __construct($registry)
*public function addPreAction($pre_action)
*public function dispatch($action, $error)
*private function execute($action)
#### 
#### loader.php #final class Loader
*private $registry
*public function __construct($registry)
*public function controller($route, $data = array())
*public function model($model, $data = array())
*public function view($template, $data = array())
*public function helper($helper)
*public function config($config)
*public function language($language)
#### 
#### model.php #abstract class Model
*protected $registry
*public function __construct($registry)
*public function __get($key)
*public function __set($key, $value)
#### 
#### registry.php #final class Registry
*private $data
*public function get($key)
*public function set($key, $value)
*public function has($key)


### system\library\
#### affiliate.php #class Affiliate
*private $affiliate_id
*private $firstname
*private $lastname
*private $email
*private $telephone
*private $fax
*private $code
*public function __construct($registry)
*public function login($email, $password)
*public function logout()
*public function isLogged()
*public function getId()
*public function getFirstName()
*public function getLastName()
*public function getEmail()
*public function getTelephone()
*public function getFax()
*public function getCode()
#### 
#### cache\apc.php #class APC
*private $expire
*private $cache
*public function __construct($expire)
*public function get($key)
*public function set($key, $value)
*public function delete($key)
#### 
#### cache\file.php #class File
*private $expire
*public function __construct($expire = 3600)
*public function get($key)
*public function set($key, $value)
*public function delete($key)
#### 
#### cache\mem.php #class Mem
*private $expire
*private $cache
*public function __construct($expire)
*public function get($key)
*public function set($key,$value)
*public function delete($key)
#### 
#### cache.php #class Cache
*private $cache
*public function __construct($driver, $expire = 3600)
*public function get($key)
*public function set($key, $value)
*public function delete($key)
#### 
#### cart.php #class Cart
*private $data
*public function __construct($registry)
*public function getProducts()
*public function add($product_id, $quantity = 1, $option = array(), $recurring_id = 0)
*public function update($cart_id, $quantity)
*public function remove($cart_id)
*public function clear()
*public function getRecurringProducts()
*public function getWeight()
*public function getSubTotal()
*public function getTaxes()
*public function getTotal()
*public function countProducts()
*public function hasProducts()
*public function hasRecurringProducts()
*public function hasStock()
*public function hasShipping()
*public function hasDownload()
#### 
#### config.php #class Config
*private $data
*public function get($key)
*public function set($key, $value)
*public function has($key)
*public function load($filename)
#### 
#### currency.php #class Currency
*private $code
*private $currencies
*public function __construct($registry)
*public function set($currency)
*public function format($number, $currency = '', $value = '', $format = true)
*public function convert($value, $from, $to)
*public function getId($currency = '')
*public function getSymbolLeft($currency = '')
*public function getSymbolRight($currency = '')
*public function getDecimalPlace($currency = '')
*public function getCode()
*public function getValue($currency = '')
*public function has($currency)
#### 
#### customer.php #class Customer
*private $customer_id
*private $firstname
*private $lastname
*private $customer_group_id
*private $email
*private $telephone
*private $fax
*private $newsletter
*private $address_id
*public function __construct($registry)
*public function login($email, $password, $override = false)
*public function logout()
*public function isLogged()
*public function getId()
*public function getFirstName()
*public function getLastName()
*public function getGroupId()
*public function getEmail()
*public function getTelephone()
*public function getFax()
*public function getNewsletter()
*public function getAddressId()
*public function getBalance()
*public function getRewardPoints()
#### 
#### db\mpdo.php #final class mPDO
*private $pdo
*private $statement
*public function __construct($hostname, $username, $password, $database, $port = '3306')
*public function prepare($sql)
*public function bindParam($parameter, $variable, $data_type = \PDO::PARAM_STR, $length = 0)
*public function execute()
*public function query($sql, $params = array())
*public function escape($value)
*public function countAffected()
*public function getLastId()
*public function __destruct()
#### 
#### db\mssql.php #final class MSSQL
*private $link
*public function __construct($hostname, $username, $password, $database, $port = '1433')
*public function query($sql)
*public function escape($value)
*public function countAffected()
*public function getLastId()
*public function __destruct()
#### 
#### db\mysql.php #final class MySQL
*private $link
*public function __construct($hostname, $username, $password, $database, $port = '3306')
*public function query($sql)
*public function escape($value)
*public function countAffected()
*public function getLastId()
*public function __destruct()
#### 
#### db\mysqli.php #final class MySQLi
*private $link
*public function __construct($hostname, $username, $password, $database, $port = '3306')
*public function query($sql)
*public function escape($value)
*public function countAffected()
*public function getLastId()
*public function __destruct()
#### 
#### db\postgre.php #final class Postgre
*private $link
*public function __construct($hostname, $username, $password, $database, $port = '5432')
*public function query($sql)
*public function escape($value)
*public function countAffected()
*public function getLastId()
*public function __destruct()
#### 
#### db.php #class DB
*private $db
*public function __construct($driver, $hostname, $username, $password, $database, $port = NULL)
*public function query($sql)
*public function escape($value)
*public function countAffected()
*public function getLastId()
#### 
#### document.php #class Document
*private $title
*private $description
*private $keywords
*private $links
*private $styles
*private $scripts
*public function setTitle($title)
*public function getTitle()
*public function setDescription($description)
*public function getDescription()
*public function setKeywords($keywords)
*public function getKeywords()
*public function addLink($href, $rel)
*public function getLinks()
*public function addStyle($href, $rel = 'stylesheet', $media = 'screen')
*public function getStyles()
*public function addScript($href, $postion = 'header')
*public function getScripts($postion = 'header')
#### 
#### encryption.php #final class Encryption
*private $key
*public function __construct($key)
*public function encrypt($value)
*public function decrypt($value)
#### 
#### image.php #class Image
*private $file
*private $image
*private $width
*private $height
*private $bits
*private $mim
*public function __construct($file)
*public function getFile()
*public function getImage()
*public function getWidth()
*public function getHeight()
*public function getBits()
*public function getMime()
*public function save($file, $quality = 90)
*public function resize($width = 0, $height = 0, $default = '')
*public function watermark($watermark, $position = 'bottomright')
*public function crop($top_x, $top_y, $bottom_x, $bottom_y)
*public function rotate($degree, $color = 'FFFFFF')
*private function filter()
*private function text($text, $x = 0, $y = 0, $size = 5, $color = '000000')
*private function merge($merge, $x = 0, $y = 0, $opacity = 100)
*private function html2rgb($color)
#### 
#### language.php #class Language
*private $default = 'english'
*private $directory
*private $data
*public function __construct($directory = '')
*public function get($key)
*public function all()
*public function load($filename)
#### 
#### length.php #class Length
*private $lengths
*public function __construct($registry)
*public function convert($value, $from, $to)
*public function format($value, $length_class_id, $decimal_point = '.', $thousand_point = ',')
*public function getUnit($length_class_id)
#### 
#### log.php #class Log
*private $handle
*public function __construct($filename)
*public function write($message)
*public function __destruct()
#### 
#### mail.php #class Mail
*protected $to
*protected $from
*protected $sender
*protected $reply_to
*protected $subject
*protected $text
*protected $html
*protected $attachments = array()
*public $protocol = 'mail'
*public $smtp_hostname
*public $smtp_username
*public $smtp_password
*public $smtp_port = 25
*public $smtp_timeout = 5
*public $newline = "\n"
*public $verp = false
*public $parameter = ''
*public function __construct($config = array())
*public function setTo($to)
*public function setFrom($from)
*public function setSender($sender)
*public function setReplyTo($reply_to)
*public function setSubject($subject)
*public function setText($text)
*public function setHtml($html)
*public function addAttachment($filename)
*public function send()
#### 
#### openbay\amazon.php #class Amazon
*private $token
*private $enc1
*private $enc2
*private $url = 'http://uk-amazon.openbaypro.com/'
*private $registry
*public function __construct($registry)
*public function __get($name)
*public function call($method, $data = array(), $is_json = true)
*public function callNoResponse($method, $data = array(), $is_json = true)
*public function encryptArgs($data)
*public function decryptArgs($crypt, $is_base_64 = true)
*public function getServer()
*public function productUpdateListen($product_id, $data = array())
*public function bulkUpdateOrders($orders)
*public function updateOrder($order_id, $order_status_string, $courier_id = '', $courier_from_list = true, $tracking_no = '')
*public function getCategoryTemplates()
*public function registerInsertion($data)
*public function insertProduct($data)
*public function updateQuantities($data)
*public function getStockUpdatesStatus($data)
*public function putStockUpdateBulk($product_id_array, $end_inactive = false)
*public function getLinkedSkus($product_id, $var='')
*public function getOrderdProducts($order_id)
*public function validate()
*public function deleteProduct($product_id)
*public function orderDelete($order_id)
*public function getOrder($order_id)
*public function getCarriers()
*public function parseCategoryTemplate($xml)
*private static function compareFields($field1, $field2)
#### 
#### openbay\amazonus.php #class Amazonus
*private $token
*private $enc1
*private $enc2
*private $url = 'http://us-amazon.openbaypro.com/'
*private $registry
*public function __construct($registry)
*public function __get($name)
*public function call($method, $data = array(), $is_json = true)
*public function callNoResponse($method, $data = array(), $is_json = true)
*public function encryptArgs($data)
*public function decryptArgs($crypt, $is_base_64 = true)
*public function getServer()
*public function productUpdateListen($product_id, $data = array())
*public function bulkUpdateOrders($orders)
*public function updateOrder($order_id, $order_status_string, $courier_id = '', $courier_from_list = true, $tracking_no = '')
*public function getCategoryTemplates()
*public function registerInsertion($data)
*public function insertProduct($data)
*public function updateQuantities($data)
*public function getStockUpdatesStatus($data)
*public function putStockUpdateBulk($product_id_array, $end_inactive = false)
*public function getLinkedSkus($product_id, $var='')
*public function getOrderdProducts($order_id)
*public function validate()
*public function deleteProduct($product_id)
*public function orderDelete($order_id)
*public function getOrder($order_id)
*public function getCarriers()
*public function parseCategoryTemplate($xml)
*private static function compareFields($field1, $field2)
#### 
#### openbay\ebay.php #final class Ebay
*private $token
*private $enc1
*private $enc2
*private $url = 'https://uk.openbaypro.com/'
*private $registry
*private $no_log = array('notification/getPublicNotifications/', 'setup/getEbayCategories/', 'item/getItemAllList/', 'account/validate/', 'item/getItemListLimited/')
*private $logger
*private $max_log_size = 50; //max log size in Mb
*public function __construct($registry)
*public function __get($name)
*public function call($call, array $post = null, array $options = array(), $content_type = 'json', $status_override = false)
*public function callNoResponse($call, array $post = null, array $options = array(), $content_type = 'json')
*private function setLogger()
*public function log($data, $write = true)
*public function decryptArgs($crypt, $is_base_64 = true)
*public function getServer()
*public function getSetting($key)
*public function getEbayItemId($product_id)
*public function getEndedEbayItemId($product_id)
*public function removeItemByItemId($item_id)
*public function removeItemByProductId($product_id)
*public function deleteProduct($product_id)
*public function orderDelete($order_id)
*public function getLiveListingArray()
*public function getEndedListingArray()
*public function getLiveProductArray()
*public function endItem($item_id)
*public function ebaySaleStockReduce($product_id, $sku = null)
*public function notifyAdmin($subject, $message)
*public function validateJsonDecode($data)
*private function eBayShippingStatus($item, $txn, $status, $tracking_no = '', $carrier_id = '')
*private function eBayPaymentStatus($item, $txn, $status)
*private function getSaleRecord($sale_id)
*public function getEbayActiveListings()
*public function getEbayItemList($limit = 100, $page = 1, $filter = array())
*public function disableProduct($product_id)
*public function disableVariant($product_id, $sku)
*public function putStockUpdate($item_id, $stock, $sku = null)
*public function putStockUpdateBulk($product_id_array, $end_inactive = false)
*public function getProductStockLevel($product_id, $sku = '')
*public function productUpdateListen($product_id, $data = array())
*public function orderStatusListen($order_id, $status_id, $data = array())
*public function decideEbayStockAction($product_id, $qty, $subtract, $sku = null)
*public function getProductId($ebay_item, $status = 0)
*public function getProductIdFromKey($key)
*public function validate()
*public function getAllocatedStock($product_id)
*public function getImages()
*private function getImageInfo($url)
*private function getImageCopy($url, $new_image)
*public function getEbayListing($item_id)
*public function relistItem($item_id, $product_id, $qty)
*public function createLink($product_id, $item_id, $variant)
*public function addReserve($data, $item_id, $variant)
*public function getReserve($product_id, $item_id, $sku = '')
*public function updateReserve($product_id, $item_id, $reserve, $sku = '', $variant = 0)
*public function deleteReserve($product_id, $item_id, $sku = '')
*public function getCarriers()
*public function getOrder($order_id)
*public function getOrderBySmpId($smp_id)
*public function updateCategories()
*public function updateSettings()
*public function updateStore()
*public function editSetting($group, $data, $store_id = 0)
*public function getShippingServiceInfo($service_code)
#### 
#### openbay\etsy.php #final class Etsy
*private $token
*private $enc1
*private $enc2
*private $url = 'https://api.openbaypro.io/'
*private $registry
*private $logger
*private $max_log_size = 50; //max log size in Mb
*public function __construct($registry)
*public function __get($name)
*public function call($uri, $method, $data = array())
*private function setLogger()
*public function log($data, $write = true)
*public function encryptArgs($data)
*public function decryptArgs($crypt, $is_base_64 = true)
*public function getServer()
*public function settingsUpdate()
*public function getSetting($key)
*public function getLinks($product_id, $status = 0, $limit = null)
*public function getLinkedProduct($etsy_item_id)
*public function updateAllStock($product_id, $new_stock)
*public function updateListingStock($etsy_item_id, $new_stock, $status)
*public function deleteProduct($product_id)
*public function deleteLink($etsy_listing_id = null, $etsy_item_id = null)
*public function productUpdateListen($product_id, $data = array())
*public function orderFind($order_id = null, $receipt_id = null)
*public function orderDelete($order_id)
*public function orderUpdatePaid($receipt_id, $status)
*public function orderUpdateShipped($receipt_id, $status)
*public function putStockUpdateBulk($product_id_array, $end_inactive)
*public function getEtsyItem($listing_id)
*public function validate()
#### 
#### openbay.php #final class Openbay
*private $registry
*private $installed_modules
*public $installed_markets
*public function __construct($registry)
*public function __get($name)
*public function log($data, $write = true)
*public function encrypt($msg, $k, $base64 = false)
*public function decrypt($msg, $k, $base64 = false)
*public function pbkdf2($p, $s, $c, $kl, $a = 'sha256')
*private function getInstalled()
*public function getInstalledMarkets()
*public function putStockUpdateBulk($product_id_array, $end_inactive = false)
*public function testDbColumn($table, $column)
*public function testDbTable($table)
*public function splitName($name)
*public function getTaxRates($tax_class_id)
*public function getTaxRate($class_id)
*public function getZoneId($name, $country_id)
*public function newOrderAdminNotify($order_id, $order_status_id)
*public function orderDelete($order_id)
*public function getProductModelNumber($product_id, $sku = null)
*public function addonLoad($addon)
*public function getUserByEmail($email)
*public function getProductOptions($product_id)
*public function getOrderProducts($order_id)
*public function getOrderProductVariant($order_id, $product_id, $order_product_id)
#### 
#### pagination.php #class Pagination
*public $total = 0
*public $page = 1
*public $limit = 20
*public $num_links = 8
*public $url = ''
*public $text_first = '|&lt;'
*public $text_last = '&gt;|'
*public $text_next = '&gt;'
*public $text_prev = '&lt;'
*public function render()
#### 
#### request.php #class Request
*public $get
*public $post
*public $cookie
*public $files
*public $server
*public function __construct()
*public function clean($data)
#### 
#### response.php #class Response
*private $headers
*private $level = 0
*private $output
*public function addHeader($header)
*public function redirect($url, $status = 302)
*public function setCompression($level)
*public function setOutput($output)
*public function getOutput()
*private function compress($data, $level = 0)
*public function output()
#### 
#### session.php #class Session
*public $data
*public function __construct($session_id = '',  $key = 'default')
*public function getId()
*public function start()
*public function destroy()
#### 
#### tax.php #final class Tax
*private $tax_rates
*public function __construct($registry)
*public function setShippingAddress($country_id, $zone_id)
*public function setPaymentAddress($country_id, $zone_id)
*public function setStoreAddress($country_id, $zone_id)
*public function calculate($value, $tax_class_id, $calculate = true)
*public function getTax($value, $tax_class_id)
*public function getRateName($tax_rate_id)
*public function getRates($value, $tax_class_id)
*public function has($tax_class_id)
#### 
#### template\php.php #class Template
*private $data
*public function set($key, $value)
*public function render()
#### 
#### template.php #class Template
*private $data
*public function __construct($driver)
*public function set($key, $value)
*public function render()
#### 
#### url.php #class Url
*private $domain
*private $ssl
*private $rewrite
*public function __construct($domain, $ssl = '')
*public function addRewrite($rewrite)
*public function link($route, $args = '', $secure = false)
#### 
#### user.php #class User
*private $user_id
*private $username
*private $permission
*public function __construct($registry)
*public function login($username, $password)
*public function logout()
*public function hasPermission($key, $value)
*public function isLogged()
*public function getId()
*public function getUserName()
*public function getGroupId()
#### 
#### weight.php #class Weight
*private $weights
*public function __construct($registry)
*public function convert($value, $from, $to)
*public function format($value, $weight_class_id, $decimal_point = '.', $thousand_point = ',')
*public function getUnit($weight_class_id)


{% include links.html %}
