# Matiks_Actionable_Insights

## Project Background:

Matiks is building the destination for competitive cognitive play. It design fast, skill-based games that test and celebrate mental agility. With thousands of users already engaging in real-time challenges, they are creating a new category at the intersection of gaming, performance and social platforms - where your mind is your edge.

**Insights and recommendations are provided on the following key areas:**

1. Revenue Trends (Weekly):

       Revenue has mostly ranged between $3K and $6K, with a notable peak at $7K around late November 2023.

       There's a recent decline to $3K in June 2025, which may need further investigation.

2. User Activity Trends:
   
       -Day-wise Activity: Daily active users hover between 300–400, peaking at 403 users on April 23(2025), but generally fluctuating.

       -Week-wise Activity: Weekly sign-ins peaked at 2,397 users (week of May 4,2025), then dropped to 1,293 by mid-May(2025).

       -Month-wise Activity: The pie chart suggests the usage of the month April and May, likely split between high-activity in the month of May(~6,972) and low-activity in the     month of April(~3,028) users.
3. Device Type & Game Mode Revenue Breakdown:
   
       -Highest revenue from:
   
        PC Co-op ($59K)
   
        Mobile Multiplayer ($58K)
   
       -Console performs well across all modes ($56K–$57K).
   
       -Mobile Solo mode brings in the lowest revenue ($54K) among the top-performing categories.

A snapshot of the **Dashborad:**

   ![image](https://github.com/user-attachments/assets/c573b432-3ee9-4b89-9f93-6e5169d5e528)
   

   **Recommendations:**

   Double Down on Mobile Multiplayer
   Mobile Multiplayer is strong ($58K) — invest in:

       Game enhancements specific to this mode.

       Targeted marketing campaigns to attract similar users.

       Referral or reward programs to boost multiplayer adoption.
   
   Given PC Co-op generates highest revenue ($59K), consider:

       Adding new levels/features.

       Creating content bundles or subscriptions.

       Leveraging streamers/influencers on PC platforms to boost visibility.

   Reactivate Lapsing Users:

       Segment by session time, in-game actions, or spend.

       Personalize offers (e.g., discounts for low-engagement users, loyalty bonuses for high-engagement ones).


  An interactive **Tableau dashboard** can be downloaded from [Link](https://public.tableau.com/app/profile/saswat.mishra8618/viz/MatiksAnalytics/MatiksMetrics) [Note: You can use the pie chart to play around the dashboard]

  Excel file regarding **Cohort Analysis** can be found here [Link](https://docs.google.com/spreadsheets/d/1jLQDGDxwwkApF8JMH79D7UOMvUX7tuo6/edit?usp=drive_link&ouid=106430923092545418901&rtpof=true&sd=true)


  ## Data Structure & Potential Queries:

  🧾 User Information

| Column Name      | Description                                       |
| ---------------- | ------------------------------------------------- |
| **User\_ID**     | A unique identifier for each user in UUID format. |
| **Username**     | The display name chosen by the user.              |
| **Email**        | User’s email address used during signup.          |
| **Signup\_Date** | The date when the user created their account.     |

🌍 Demographics

| Column Name | Description                                 |
| ----------- | ------------------------------------------- |
| **Country** | Country from which the user signed up.      |
| **Age**     | Age of the user at the time of signup.      |
| **Gender**  | User's gender (can be Male, Female, Other). |

📱 Device & Game Behavior

| Column Name                     | Description                                                       |
| ------------------------------- | ----------------------------------------------------------------- |
| **Device\_Type**                | The platform used to access the game (e.g., Mobile, PC, Console). |
| **Game\_Title**                 | The specific game that the user played.                           |
| **Total\_Play\_Sessions**       | Number of gaming sessions the user has played.                    |
| **Avg\_Session\_Duration\_Min** | Average duration (in minutes) of each play session.               |
| **Total\_Hours\_Played**        | Total time (in hours) spent playing games.                        |

💰 Monetization Data

| Column Name                    | Description                                                               |
| ------------------------------ | ------------------------------------------------------------------------- |
| **In\_Game\_Purchases\_Count** | Number of purchases made by the user within the game (microtransactions). |
| **Total\_Revenue\_USD**        | Total money spent by the user in USD.                                     |


📆 Engagement & Subscription

| Column Name            | Description                                                                    |
| ---------------------- | ------------------------------------------------------------------------------ |
| **Last\_Login**        | The most recent date the user logged into the platform.                        |
| **Subscription\_Tier** | The level of subscription the user holds (e.g., Free, Silver, Gold, Platinum). |

📣 User Acquisition & Preferences

| Column Name               | Description                                                                      |
| ------------------------- | -------------------------------------------------------------------------------- |
| **Referral\_Source**      | How the user found the game (e.g., Friend, Ads, Organic, Social Media).          |
| **Preferred\_Game\_Mode** | Game mode most played or preferred by the user (e.g., Solo, Co-op, Multiplayer). |


🏆 Progress & Status

| Column Name            | Description                                                                                        |
| ---------------------- | -------------------------------------------------------------------------------------------------- |
| **Rank\_Tier**         | Competitive rank of the user based on performance (e.g., Bronze, Silver, Gold, Diamond, Platinum). |
| **Achievement\_Score** | A numerical score that reflects total in-game achievements earned by the user.                     |

You can access the data from here [Link](https://drive.google.com/file/d/1rMRtNN-NgFmAeb36pwQqdxlNBM-OcDNW/view?usp=sharing)

SQL queries utilized to inspect and analyze the data [Link](https://drive.google.com/file/d/1HE5dZKZ20KhtukjqSP9fIm7UQbKz2m4_/view?usp=sharing)



