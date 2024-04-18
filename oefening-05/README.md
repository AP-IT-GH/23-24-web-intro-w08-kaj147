# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /top-headlines.
3. Voeg een X-Api-Key header toe met je API-sleutel.
4. Voer het verzoek uit en bekijk de respons.
https://newsapi.org/v2/top-headlines?sources=techcrunch&apiKey=7d002eeb35e24e849e27f117de658231

kreeg error dat sources erbij moest dus heb van voorbeeld techcrunch gepakt

{
    "status": "ok",
    "totalResults": 10,
    "articles": [
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Manish Singh",
            "title": "India scrambles to curb PhonePe and Google's dominance in mobile payments | TechCrunch",
            "description": "The National Payments Corporation of India (NPCI), the governing body overseeing the country's widely used Unified Payments Interface (UPI) mobile payment NPCI is set to engage with various fintech startups this month to develop a strategy to address the grow…",
            "url": "https://techcrunch.com/2024/04/16/india-scrambles-to-curb-phonepe-and-google-dominance-in-mobile-payments/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2022/06/GettyImages-1213174164.jpg?resize=1200,800",
            "publishedAt": "2024-04-17T04:31:09Z",
            "content": "The National Payments Corporation of India (NPCI), the governing body overseeing the country’s widely used Unified Payments Interface (UPI) mobile payment system, is set to engage with various fintec… [+2349 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Ingrid Lunden",
            "title": "Flatpay rings up $47M to target smaller merchants with simple payment solutions | TechCrunch",
            "description": "As the world waits for $65 billion payments tech giant Stripe to go public, a wave of smaller startups continues to roll into the market to pick up more",
            "url": "https://techcrunch.com/2024/04/16/flatpay-rings-up-47m-to-target-smaller-merchants-with-simple-payment-solutions/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2024/04/Screenshot-2024-04-17-at-01.53.22.png?resize=1200,958",
            "publishedAt": "2024-04-17T00:56:56Z",
            "content": "As the world waits for $65 billion payments tech giant Stripe to go public, a wave of smaller startups continues to roll into the market to pick up more payments business. In one of the latest develo… [+5527 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Aria Alamalhodaei",
            "title": "Former top SpaceX exec Tom Ochinero sets up new VC firm, filings reveal | TechCrunch",
            "description": "Former senior SpaceX executive Tom Ochinero is teaming up with SpaceX alum-turned-VC, Achal Upadhyaya, and one of Sequoia’s top finance leaders, Spencer",
            "url": "https://techcrunch.com/2024/04/16/former-top-spacex-exec-tom-ochinero-sets-up-new-vc-firm-filings-reveal/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2022/03/51924933910_9627ae096e_o.jpg?resize=1200,800",
            "publishedAt": "2024-04-16T22:01:02Z",
            "content": "Former senior SpaceX executive Tom Ochinero is teaming up with SpaceX alum-turned-VC, Achal Upadhyaya, and one of Sequoias top finance leaders, Spencer Hemphill, on a new venture called Interlagos Ca… [+2253 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Rebecca Bellan",
            "title": "Waymo begins robotaxi testing in Atlanta | TechCrunch",
            "description": "Waymo began testing its robotaxis in Atlanta, adding another city to its ever-expanding testing and deployment domain.",
            "url": "https://techcrunch.com/2024/04/16/waymo-begins-robotaxi-testing-in-atlanta/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2020/03/Waymo-dome.jpg?resize=1200,675",
            "publishedAt": "2024-04-16T21:55:32Z",
            "content": "Waymo, the self-driving company under Alphabet, began testing its robotaxis in Atlanta on Tuesday, adding another city to its ever-expanding testing and deployment domain.\r\nOver the next few months, … [+3284 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Maggie Stamets, Dominic-Madori Davis and Rebecca Szkutak",
            "title": "FLO is improving EV charging infrastructure | TechCrunch",
            "description": "Founded by Louis Tremblay, FLO is looking to build robust EV charging infrastructure that will create a reliable web for drivers to get to where they need to go.",
            "url": "https://techcrunch.com/2024/04/16/flo-is-improving-ev-charging-infrastructure/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2024/04/GettyImages-1243697040.jpg?w=1024",
            "publishedAt": "2024-04-16T21:10:03Z",
            "content": "The lack of charging infrastructure is a major barrier to entry for those looking to convert gas-powered vehicles to electric.\r\nThis process is an essential component of fighting climate change, and … [+2298 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Rebecca Bellan and Sean O'Kane",
            "title": "Tesla ditches EV inventory discounts to 'streamline' sales and delivery | TechCrunch",
            "description": "Tesla has ended discounts on inventory across its entire electric vehicle lineup as part of a plan by CEO Elon Musk to \"streamline\" sales.",
            "url": "https://techcrunch.com/2024/04/16/tesla-ditches-ev-inventory-discounts-to-streamline-sales-and-delivery/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2018/09/GettyImages-1010166584.jpg?w=1024",
            "publishedAt": "2024-04-16T20:59:33Z",
            "content": "Tesla has ended discounts on inventory across its entire electric vehicle lineup — even as sales for EVs have flagged — as part of a larger and vague plan by CEO Elon Musk to “streamline the whole Te… [+3724 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Marina Temkin, Connie Loizos and Alex Wilhelm",
            "title": "HR startup Rippling is in discussions to raise at a $13.4B valuation, up from $11.25B | TechCrunch",
            "description": "Late stage HRtech startup Rippling is raising new capital. The company’s new round, that has not yet closed, would inject $200 million into Rippling with",
            "url": "https://techcrunch.com/2024/04/16/hr-startup-rippling-is-in-discussions-to-raise-at-a-13-4b-valuation-up-from-11-25b/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2022/10/TechCrunch-Disrupt-Haje-Kamps-831.jpg?resize=1200,800",
            "publishedAt": "2024-04-16T20:42:28Z",
            "content": "Late stage HRtech startup Rippling is raising new capital. The companys new round, that has not yet closed, would inject $200 million into Rippling with another $670 million worth of shares being sol… [+2413 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Devin Coldewey",
            "title": "Space startups are licking their lips after NASA converts $11B Mars mission into a free-for-all | TechCrunch",
            "description": "Considering how heavily both primes and space startups have been investing in interplanetary capability, this announcement arguably amounts to a historic windfall.",
            "url": "https://techcrunch.com/2024/04/16/space-startups-licking-their-lips-after-nasa-converts-11b-mars-mission-into-a-free-for-all/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2024/04/msr-lander.webp?resize=1200,665",
            "publishedAt": "2024-04-16T20:37:03Z",
            "content": "NASA Administrator Bill Nelson has pronounced the agency’s $11 billion, 15-year mission to collect and return samples from Mars: insufficient. But the strategy shift could be a huge boon to space sta… [+3793 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Haje Jan Kamps",
            "title": "Kickstarter launches pre-orders for completed campaigns | TechCrunch",
            "description": "Once a Kickstarter campaign is complete, you need to turn to a creator's own page to pre-order the products -- that is, until now. Today, Kickstarter",
            "url": "https://techcrunch.com/2024/04/16/kickstarter-late-pledges/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2018/03/kickstarter-ios-icon_preview.jpg?resize=1200,675",
            "publishedAt": "2024-04-16T20:04:42Z",
            "content": "Once a Kickstarter campaign is complete, you need to turn to a creator’s own page to pre-order the products — that is, until now. Today, Kickstarter announces that it is (finally!) including pre-orde… [+3724 chars]"
        },
        {
            "source": {
                "id": "techcrunch",
                "name": "TechCrunch"
            },
            "author": "Kyle Wiggers",
            "title": "Intel and others commit to building open generative AI tools for the enterprise | TechCrunch",
            "description": "Intel and other tech heavyweights say they'll work together to build open generative AI tools for businesses, as part of a new Linux Foundation organization.",
            "url": "https://techcrunch.com/2024/04/16/intel-and-others-commit-to-building-open-generative-ai-tools-for-the-enterprise/",
            "urlToImage": "https://techcrunch.com/wp-content/uploads/2024/04/opea-img2.png",
            "publishedAt": "2024-04-16T19:20:41Z",
            "content": "Can generative AI designed for the enterprise (e.g. AI that autocompletes reports, spreadsheet formulas and so on) ever be interoperable? Along with a coterie of organizations including Cloudera and … [+4718 chars]"
        }
    ]
}