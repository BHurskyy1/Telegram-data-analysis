# Telegram-data-analysis
NaUKMA Computational Social Science course final project.
The project works with two types of data: Users connected to me and messages I sent and received.
All the analysis was made with pandas.

### I've made 20 plots showing some pretty interesting stats.
Plots and stats were made with pandas, matplotlib, plotly.

## How to download?
1. Install dependencies: pip install -r requirements.txt
2. Get your credentials https://my.telegram.org/apps
3. Set credentials in config/config.json
4. Download '0_download_dialogs_list.py' and '1_download_dialogs_data.py'
5. Download dialogues data python 1_download_dialogs_data.py --dialogs_ids -1 --dialog_msg_limit 100000 // message limit is 100000
6. Download all dialogues python 0_download_dialogs_list.py --dialogs_limit -1 
7. Specify where you saved 'dialogs_data_all.csv' and 'dialogs_users_all.csv' in 'my_research.ipynb'
DIALOGS_MERGED_DATA_ALL_PATH = "/your path/dialogs_data_all.csv"
DIALOGS_MERGED_DATA_USERS_ALL_PATH = "/your path/dialogs_users_all.csv"

## Some studies made.
* Most used words Wordclouds
* Favourite stickers
* Sent/received correlation
* Funny messages percentage
* My telegram activity stats(hours of activity, voice messages length)
* Messages I save
* Curse words usage in group chats
* Messages with links
         
## What studies can be done next?
* NLP
* News analysis
* Punctuation mistakes
* Attitude towards countries/leaders
* Citation index (fwd messages)

P.S. Untitleddesign11.png is a mask for one of the Wordclouds
P.S. 2 Here is the "favourite stickers graph", plotly can't work properly with github preview due to js
![newplot (1)](https://user-images.githubusercontent.com/84453245/167308026-817534e2-5785-4ab5-a79c-cc3a11e42533.png)
