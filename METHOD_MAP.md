| SDK method | Resource file | HTTP method| Endpoint | Documentation |
|------------|---------------|------------|----------|---------------|
| list_campaigns | resources/campaigns.py | GET | /v2/campaigns | https://yandex.ru/dev/market/partner-api/doc/ru/reference/campaigns/getCampaigns |
| get_campaign | resources/campaigns.py | GET | /v2/campaigns/{campaignId} | https://yandex.ru/dev/market/partner-api/doc/ru/reference/campaigns/getCampaign |
| get_campaign_settings | resources/campaigns.py | POST | /v2/campaigns/{campaignId}/settings | https://yandex.ru/dev/market/partner-api/doc/ru/reference/campaigns/getCampaignSettings |
| get_business_settings | resources/businesses.py | POST | /v2/businesses/{businessId}/settings | https://yandex.ru/dev/market/partner-api/doc/ru/reference/businesses/getBusinessSettings |
| get_category_tree | resources/categories.py | POST | /v2/categories/tree | https://yandex.ru/dev/market/partner-api/doc/ru/reference/categories/getCategoriesTree |
| list_category_parameters | resources/categories.py | POST | /v2/category/{categoryId}/parameters | https://yandex.ru/dev/market/partner-api/doc/ru/reference/content/getCategoryContentParameters |
| update_offer_mappings| resources/offers.py | POST | /v2/businesses/{businessId}/offer-mappings/update | https://yandex.ru/dev/market/partner-api/doc/ru/reference/business-assortment/updateOfferMappings |
| update_campaign_offers | resources/offers.py | POST | /v2/campaigns/{campaignId}/offers/update | https://yandex.ru/dev/market/partner-api/doc/ru/reference/assortment/updateCampaignOffers |
| generate_offer_barcodes | resources/offers.py | POST | /v1/businesses/{businessId}/offer-mappings/barcodes/generate | https://yandex.ru/dev/market/partner-api/doc/ru/reference/business-offer-mappings/generateOfferBarcodes |
| get_offer_cards_status | resources/offers.py | POST | /v2/businesses/{businessId}/offer-cards | https://yandex.ru/dev/market/partner-api/doc/ru/reference/content/getOfferCardsContentStatus |
| update_offer_cards | resources/offers.py | POST | /v2/businesses/{businessId}/offer-cards/update | https://yandex.ru/dev/market/partner-api/doc/ru/reference/content/updateOfferContent |
| list_offer_mappings | resources/offers.py | POST | /v2/businesses/{businessId}/offer-mappings | https://yandex.ru/dev/market/partner-api/doc/ru/reference/business-assortment/getOfferMappings |
| list_campaign_offers | resources/offers.py | POST | /v2/campaigns/{campaignId}/offers | https://yandex.ru/dev/market/partner-api/doc/ru/reference/assortment/getCampaignOffers |
| delete_offer_mappings | resources/offers.py | POST | /v2/businesses/{businessId}/offer-mappings/delete | https://yandex.ru/dev/market/partner-api/doc/ru/reference/business-assortment/deleteOffers |
| delete_campaign_offers | resources/offers.py | POST | /v2/campaigns/{campaignId}/offers/delete | https://yandex.ru/dev/market/partner-api/doc/ru/reference/assortment/deleteCampaignOffers |
| list_hidden_campaign_offers | resources/offers.py | GET | /v2/campaigns/{campaignId}/hidden-offers | https://yandex.ru/dev/market/partner-api/doc/ru/reference/assortment/getHiddenOffers |
| hide_campaign_offers | resources/offers.py | POST | /v2/campaigns/{campaignId}/hidden-offers | https://yandex.ru/dev/market/partner-api/doc/ru/reference/assortment/addHiddenOffers |
| unhide_campaign_offers | resources/offers.py | POST | /v2/campaigns/{campaignId}/hidden-offers | https://yandex.ru/dev/market/partner-api/doc/ru/reference/assortment/deleteHiddenOffers |
| archive_offer_mappings | resources/offers.py | POST | /v2/businesses/{businessId}/offer-mappings/archive | https://yandex.ru/dev/market/partner-api/doc/ru/reference/business-assortment/addOffersToArchive |
| unarchive_offer_mappings | resources/offers.py | POST | /v2/businesses/{businessId}/offer-mappings/unarchive | https://yandex.ru/dev/market/partner-api/doc/ru/reference/business-assortment/deleteOffersFromArchive |
| generate_barcodes_report | resources/reports.py | POST | /v1/reports/documents/barcodes/generate | https://yandex.ru/dev/market/partner-api/doc/ru/reference/reports/generateBarcodesReport |