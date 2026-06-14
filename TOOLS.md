# Tools: Danielle Perry

## Tool Usage

### Connected Services

These are local mock API histories the agent may read and reference for Danielle. Live actions (sending, purchasing, scheduling with others, irreversible changes) are gated by the Confirmation Rules in AGENTS.md. The accounts Danielle actively manages day to day are listed in MEMORY.md > Connected Accounts; everything below is reference history only.

#### Communication and Scheduling

- **Gmail** (`gmail-api`): Personal email history for reading and drafting on Danielle's behalf.
- **Google Calendar** (`google-calendar-api`): Work blocks, custody weekends, appointments, and Kenosha visits.
- **Google Contacts** (`google-contacts-api`): Verified contact details checked before addressing anyone.
- **Outlook** (`outlook-api`): Secondary mail history retained for older correspondence.
- **WhatsApp** (`whatsapp-api`): Family and fishing-group messaging history.
- **Telegram** (`telegram-api`): Occasional group threads and channels.
- **Signal** (`signal-api`): Private one-to-one messaging history.
- **Discord** (`discord-api`): A couple of hobby and trades communities.
- **Zoom** (`zoom-api`): Rare video calls with family or providers.
- **Google Meet** (`google-meet-api`): Occasional school or provider video meetings.
- **Calendly** (`calendly-api`): Booking links used when a provider sends one.
- **GroupMe** (`groupme-api`): Volleyball-parent and neighbor coordination threads.

#### Shopping and Marketplaces

- **Amazon Shopping** (`amazon-shopping-api`): Buyer-side ordering and product research for tools and home goods.
- **Walmart** (`walmart-api`): Everyday household and grocery purchases.
- **Target** (`target-api`): Occasional household and Sophie-related shopping.
- **Costco** (`costco-api`): Bulk staples and tires.
- **eBay** (`ebay-api`): Used and discontinued truck and tool parts.
- **Etsy** (`etsy-api`): Occasional gifts.
- **Home Depot** (`home-depot-api`): HVAC parts, water heaters, and side-job materials.
- **Lowes** (`lowes-api`): Alternate source for home-improvement materials.
- **Menards** (`menards-api`): Regional Midwest hardware and supplies.
- **Best Buy** (`bestbuy-api`): Phones, chargers, and small electronics.
- **Kohls** (`kohls-api`): Clothing and household basics.
- **Carhartt** (`carhartt-api`): Work clothing and gear.
- **Harbor Freight** (`harbor-freight-api`): Affordable tools and shop supplies.
- **AutoZone** (`autozone-api`): Truck maintenance parts and fluids.
- **OReilly Auto Parts** (`oreilly-auto-api`): Alternate auto-parts source.
- **Grainger** (`grainger-api`): Industrial and HVAC components.

#### Food and Grocery

- **DoorDash** (`doordash-api`): Occasional delivery on long days.
- **Uber Eats** (`ubereats-api`): Alternate food delivery.
- **Grubhub** (`grubhub-api`): Backup delivery option.
- **Instacart** (`instacart-api`): Grocery delivery when time is short.
- **OpenTable** (`opentable-api`): Reservations for dinners with Sophie.
- **Yelp** (`yelp-api`): Finding reliable, no-fuss restaurants and local services.
- **Starbucks** (`starbucks-api`): Occasional coffee runs.
- **Dominos** (`dominos-api`): Easy weeknight pizza.
- **Chipotle** (`chipotle-api`): Quick reliable meals.
- **Aldi** (`aldi-api`): Budget grocery shopping.

#### Home, Local, Travel, and Weather

- **Google Maps** (`google-maps-api`): Routing to job sites and personal stops.
- **Waze** (`waze-api`): Traffic-aware routing during commutes.
- **Uber** (`uber-api`): Rides when the truck is in the shop.
- **Lyft** (`lyft-api`): Alternate rideshare.
- **Airbnb** (`airbnb-api`): Occasional weekend or fishing-trip lodging.
- **Booking** (`booking-api`): Hotel comparison for trips.
- **Expedia** (`expedia-api`): Combined travel booking and comparison.
- **Amadeus** (`amadeus-api`): Flight search for rare travel.
- **Tripadvisor** (`tripadvisor-api`): Reviews when planning trips.
- **GasBuddy** (`gasbuddy-api`): Finding the cheapest nearby fuel.
- **Zillow** (`zillow-api`): Casual local housing and rental research.
- **Nextdoor** (`nextdoor-api`): Neighborhood updates and recommendations.

#### Weather

- **OpenWeather** (`openweather-api`): Conditions for fishing and rooftop work.
- **Weather Channel** (`weather-channel-api`): Forecasts and severe-weather alerts.
- **AccuWeather** (`accuweather-api`): Hourly detail for job planning.

#### Money and Insurance

- **Plaid** (`plaid-api`): Read-only account aggregation for budgeting.
- **PayPal** (`paypal-api`): Occasional online payments and side-job transfers.
- **Venmo** (`venmo-api`): Splitting costs with Mike and family.
- **Zelle** (`zelle-api`): Quick bank-to-bank transfers.
- **Cash App** (`cashapp-api`): Backup peer payments.
- **Capital One** (`capital-one-api`): Quicksilver card paid monthly.
- **GEICO** (`geico-api`): Auto insurance policy reference.
- **State Farm** (`state-farm-api`): Renters insurance policy reference.
- **UnitedHealthcare** (`unitedhealthcare-api`): Health plan benefits reference.
- **Mint** (`mint-api`): Budget tracking against monthly targets.
- **Credit Karma** (`creditkarma-api`): Credit monitoring while rebuilding savings.
- **NerdWallet** (`nerdwallet-api`): Comparing cards, rates, and insurance.

#### Health and Fitness

- **GoodRx** (`goodrx-api`): Prescription price comparison for atorvastatin and supplements.
- **CVS** (`cvs-api`): Pharmacy refills and store pickup.
- **Walgreens** (`walgreens-api`): Alternate pharmacy.
- **Caremark** (`caremark-api`): Prescription benefit management.
- **MyFitnessPal** (`myfitnesspal-api`): Tracking diet changes for cholesterol.
- **Strava** (`strava-api`): Logging evening walks.
- **Calm** (`calm-api`): Sleep and stress support before early shifts.
- **Headspace** (`headspace-api`): Short guided sessions.
- **Cronometer** (`cronometer-api`): Nutrient detail for reducing red meat.
- **Fooducate** (`fooducate-api`): Quick grocery nutrition checks.

#### Media and Entertainment

- **Spotify** (`spotify-api`): Classic rock and country on long drives.
- **YouTube** (`youtube-api`): Repair walkthroughs and music.
- **Netflix** (`netflix-api`): Evening streaming.
- **ESPN** (`espn-api`): Bears, Cubs, and Blackhawks coverage.
- **Hulu** (`hulu-api`): Backup streaming.
- **TMDB** (`tmdb-api`): Looking up shows and films.
- **OpenLibrary** (`openlibrary-api`): Library thrillers and audiobooks.
- **Audible** (`audible-api`): Audiobooks for long drives.
- **Kindle** (`kindle-api`): Occasional e-reading.
- **Pandora** (`pandora-api`): Radio-style music.
- **iHeartRadio** (`iheartradio-api`): Stations and podcasts.
- **Twitch** (`twitch-api`): Occasional streams.
- **Vimeo** (`vimeo-api`): Saved trade and how-to videos.
- **SoundCloud** (`soundcloud-api`): Music and shows.
- **Ticketmaster** (`ticketmaster-api`): Game and concert tickets.
- **Eventbrite** (`eventbrite-api`): Local events.

#### Social and Community

- **Instagram** (`instagram-api`): Following Sophie and fishing accounts.
- **Twitter** (`twitter-api`): Sports and local news.
- **Reddit** (`reddit-api`): HVAC, fishing, and trades communities.
- **Pinterest** (`pinterest-api`): Project and recipe ideas.
- **LinkedIn** (`linkedin-api`): Professional presence in the trade.
- **Craigslist** (`craigslist-api`): Used tools and truck accessories.
- **Meetup** (`meetup-api`): Occasional fishing or trades meetups.
- **Snapchat** (`snapchat-api`): Staying in touch with Sophie.

#### Documents and Storage

- **Google Drive** (`google-drive-api`): Receipts, warranties, and side-job notes.
- **Dropbox** (`dropbox-api`): Backup of photos and documents.

#### Not Connected

- Live web search, web browsing, and deep internet research are unavailable; the agent works only from these mock histories, stored memory, and Danielle's instructions.
- Employer systems, dispatch software, shop work orders, banking apps, provider portals, and Facebook are not connected to OpenClaw; treat them as off-limits and work only from Danielle's instruction and stored memory.
- Do not infer live access to external accounts; financial transactions, outbound messages, medical/childcare/work scheduling, and irreversible changes require confirmation per AGENTS.md.
