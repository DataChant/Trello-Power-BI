# Trello-Power-BI
<img width="972" height="337" alt="image" src="https://github.com/user-attachments/assets/97c36b24-0aca-4a40-9b1f-64c432fb7907" />

This is an open source repo for Microsoft Fabric, Power BI and Power Query users to connect to your Trello account and analyze your boards using Power Query / DAX


# Instructions
1. Clone the repository
2. Install the latest Power BI Desktop
3. Open Trello.pbip using Power BI Desktop
4. Select Transform Data >> Edit parameters
5. In Edit Parameters, replace API Key and API Token with the keys from your Trello account. Learn [here](https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/) how to obtain the API Key and Token.
<img width="700" height="325" alt="image" src="https://github.com/user-attachments/assets/10b846c5-6030-4545-875e-4a03ac86bc6d" />

6. Click OK, and refresh the report.
7. To speed up the refresh time, you can limit the import of Trello Actions. For example, enter 30 in **Last N Days Actions** to load only the last 30 days of actions (Card moves, Comments, Completed items in Checklists).

# Clarification
The main purpose of this source code is the implementation in Power Query and the Semantic Model. The current visualaziations were created for specific use cases.



Need a customized version? Contact us at support@datachant.com
