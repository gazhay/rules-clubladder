# Club Ladder Race Book

The league is a team based one operating in a [ladder tournament](https://en.wikipedia.org/wiki/Ladder_tournament) format, each team can challenge others above them in the league to a race, which is then run in a 5 v 5 rider format with race points allocated based on finishing position, the team with the highest number of race points is the winner.

The result is then recorded in the league. The league is run in a leapfrog format, this format is commonly used in racquet sports. Teams are free to choose who to play by challenging teams up to 7 above them in the table. If they win they take the loser's position and everyone below moves down a position, hence they leapfrog up the table.

Teams are bound by an allowed range in rider zMAP value as we believe it reflects balanced team rosters (and thus good races)  as it is simple and thus scalable for the series and systems involved.
(Historically teams were bound by ZwiftRacing.app vELO1 rankings, rather than relying on legacy Zwiftpower categories.)
The league mixes all teams, all rankings, together in one league, allowing for a strong team at the upper end of one ranking level to challenge themselves against lower ranked teams of the ranking level above.

1. **[Joining The Ladder](joining.md).**
2. **[Rules](rules.md).**
3. **[Sanctions](sanctions.md).**
4. **[Scoring](scoring.md).**
5. **[Route Selection](route-selection.md).**
6. **[Race refereeing](refereeing.md).**


# 🔁 Transfer Windows & ‘Seasons’

The league is ongoing at all times and teams may join and leave at any time. 'Seasons' are usually reserved for major changes to ladder setup, however the ladder is broken up by transfer windows every 60 days, during which riders can move between teams, teams can move between leagues, or during which race control might implement rule changes.

These windows will run for the last 7 days of February, April, June, August, October and December.

Teams must retain a minimum of 5 core riders during a transfer window, if they wish to change more riders then the team should be removed and a new team entered.

At the end of the transfer window, teams must meet the “3 rank spread rule”, so any riders who have gone beyond rank should be moved at this point. When adding or removing riders, teams must continue to stay bound by the “3 rank spread” rule. However should teams wish to adjust their rank spread they can do so by ensuring riders are removed and added in the right order.

*Eg. If a team is currently ranked Platinum to Sapphire, they can add Emerald riders by first removing their Platinum riders.*
However note this will (deliberately) limit the change in rank you can make in any off season to +2 from your current. If you wish to change rank by greater than this, it will be treated as a new team so you should delete your current team and enter a new one.

At each transfer window we will set out any changes to:

- Minimum race frequency (this may vary according to the wider calendar at that time.)
- Mandatory race dates.

On a more infrequent basis we will need to move to a new season for admin purposes, this will most likely happen at September of every year but may happen at other ad hoc times depending on admin requirements.

# 📉 Rider Performance, Spot Checks & Verification

A number of automated checks are in place to analyse rider performance and help ensure fair racing, we access our data directly from Zwift and may have access to additional information to what you might see in 3rd party tools such as Strava. The most current common checks are highlighted below, however these are not exhaustive and we simply ask that riders ride a bike “normally and like you would in real life” and always ride within the spirit of the rules, as well as within the rules. Race Control will always reserve the right to remove riders for performances or techniques that seem unusual.

The exact parameters of each check will not be published, and are constantly under review and adjustment as we gather more learnings from our events.

## World Class Ability

Riders power curves are regularly checked against commonly accepted power figures for professional or world class performance at their age grade. Any rider putting out such figures will be asked by race control to [verify their ability in a number of ways](https://github.com/gazhay/rules-clubladder/blob/main/docs/index.md#-world-class-verification-process) including comparable real life performance or a verified performance test by ZADA or another similar body. Riders may continue to race while pending verification but will not be allowed to continue in ladder if verification is not provided in a timely manner.

The team captain of any rider receiving a World Class DQ will be contacted directly by race control  within 24 hours for further information if required.

## Unusual Style/Technique

These are defined similar to other community run events. Our intention is to spot and outlaw techniques that are likely to create benefit from things such as “sticky watts” or “micro bursts”, typically these involve a highly variable or "staccato” cadence style. Normally this is easily visible in your power or cadence data as a highly variable trace versus a more steady normal trace.

<img width="310" height="75" alt="Trace_Comparison" src="https://github.com/user-attachments/assets/cf0a4071-a8ba-4040-b555-2e936361ea4a" />

DQ for unusual technique is automatic, with a manual check from race control to validate so there may be some delay until the DQ is finalised. This DQ will be visible in the results so race control will not typically contact captains to discuss further. There is no appeals process. Typically any review is undertaken within 24 hours, so any disqualification still in place after this time should be treated as final.

## Sticky Watts

This is very visible from a flat top on the power curve like shown. In most instances where such a flat top is visible it will be an automatic DQ, however other considerations such as cadence, period and frequency of flat tops may be taken into account.

<img width="128" height="55" alt="Untitled 1" src="https://github.com/user-attachments/assets/b27f3a1d-5dbe-42f2-9a3e-54e3a242f1d7" />


DQ for sticky watts is automatic, and is for the most part an “open and shut case” as the system is accurate in spotting this. The main instances of false positives is where riders have significant device or equipment issues which cause the sticky watts. However as Sticky Watts and Equipment Issues both constitute a minor infringement, race control do not investigate these further as both are punished the same. As a captain you may well want to investigate the issue with your rider to help resolve future issues. Please see the guide [here](https://github.com/gazhay/rules-clubladder/blob/main/docs/index.md#sticky-wattequipment-analysis).

## Equipment Requirements

A number of equipment requirements exist in Ladder.

- No Zpower (or any device which estimates power in a similar manner, such as power pod).
- No “spin” or “exercise” bikes.
- Where riders have access to multiple power meters, they must pair trainer/bike as the primary power source for in game measurement.
- A controllable trainer/bike must be connected if the rider has one.
These will be checked through random [Rider Spot Check](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#rider-spot-check).

# ❔ ‘How To’ Guides

## Team Registration

1. Visit the Club Ladder [website](https://ladder.cycleracing.club/) and click “Captain Registration”
2. Fill out the form with the required information and a valid email address.
3. You will need to click on the link in the email that gets sent to you to be approved for access.

## Rider Registration

There is no requirement for a rider to create an account on the ladder website, however by doing so you can gain access to a range of stats and information related to your team and upcoming opponents.

1. Visit the Club Ladder website [https://ladder.cycleracing.club](https://ladder.cycleracing.club/) and click “Sign In” under the riders heading. (note you can still use Data Consent & Spot Check without an account)

<img width="250" height="300" alt="1000044210" src="https://github.com/user-attachments/assets/227b0361-ec09-471e-b206-8ca6896c2dec" />

1. Sign in for riders is only using Google or Discord SSO options, this means race control cannot directly help with login issues.
2. You will need to input your Zwift ID to verify yourself as a current active ladder participant.

Note: Discord remains captains only, and all communication with race control should still go through captains.

## Linking / Unlinking with Zwift (new data consent)

To be eligible to race, riders must Link their Zwift account with Ladder - [https://ladder.cycleracing.club/](https://ladder.cycleracing.club/editself) when joining for the first time.

<img width="500" height="200" alt="Link_with_Zwift" src="https://github.com/user-attachments/assets/50e6092f-73b3-4caf-8a77-9056dfdf6885" />

Clicking ‘Login with Zwift’ redirects them to sign in with their Zwift login credentials.

This is an **official** link with Zwift. Riders who do not link with Zwift will be unable to participate in Ladder, and will be excluded from all scoring results.

**What we get;**

- Access to your activity data for scoring and verification purposes.
- Access to your profile data to verify identity and metrics.

**What we do not get;**

- Your login details - You are logging in to Zwift directly and they are then authorising us limited access to your data.

Once linked successfully you will get a confirmation:

<img width="500" height="120" alt="Account_linked_sucessfully" src="https://github.com/user-attachments/assets/7d47dcc7-bfcb-4e7c-a5c7-90125766188e" />

If the rider is on a roster this can also be verified by the Z icon next to their name:

<img width="261" height="40" alt="Rider_linked_Z 1" src="https://github.com/user-attachments/assets/00310829-694e-4956-9c9f-f05449bb1395" />

If you later change your mind, you will be able to remove the link in your account page - [https://ladder.cycleracing.club/editself](https://ladder.cycleracing.club/editself).

<img width="500" height="280" alt="Unlink_from_Zwift" src="https://github.com/user-attachments/assets/c7a445b0-e1b4-4a9d-be3a-3f0f5b0b1789" />

If a rider on a roster has unlinked their Zwift account, there will be a warning triangle next to their name in place of the Z icon:

<img width="91" height="61" alt="image 2" src="https://github.com/user-attachments/assets/bea843dd-b10e-4585-b884-67936bab70af" />

## Creating & Editing A Team

1. Upon first login you will be greeted with “Register a team” button. You must create your team using the following format to differentiate between different teams from the same club: “Clubname” “Team Name””. Eg. “ESCO Picklebacks”. Complete all other details in the profile setup.
2. Navigate to the “Team” tab [1] and add your riders by their Zwift ID [2]. After riders have been added and undertaken their first race, they will be locked into the roster until the next transfer window.

<img width="550" height="305" alt="image(1)" src="https://github.com/user-attachments/assets/acdd3a6b-1d86-461d-9851-1841c3caa966" />

3. As you add riders, the system will visualise which ranks can still be added to the team to keep it within the 3 rank spread rule. Your first rider can be anyone, after that it will show you which riders could be added and stay in range. *eg. Below I have added only bronze riders, so you could add any of these ranks and stay within a range of 3. If in this example you were to add a copper rider, the range would reduce so you could then only add to silver.*

<img width="259" height="154" alt="Untitled 2" src="https://github.com/user-attachments/assets/a61bf9b7-77ba-4c96-bd10-28cb71b9c93a" />

4. Riders who are eligible to be removed (see [👨‍⚖️ Rules](Club%20Ladder%20Race%20Book%20402167d503d080648570cb89af896829.md)  - been inactive on ladder for a certain period etc.) may be removed from the roster by pressing the red X on the right of their stats. This is the same process for removing riders during the transfer window.

<img width="270" height="195" alt="Untitled" src="https://github.com/user-attachments/assets/00c1d244-4809-4faa-874d-1a087298a278" />

## Accepting / Creating an Auction Offer

The preferred method of creating a challenge is using the “availability auction” feature.

Once you know your team availability for a specific day and time, first check on your team dashboard to see if a team within your challenge range has an existing offer you can accept:

<img width="750" height="260" alt="Available_Offers" src="https://github.com/user-attachments/assets/d416f3f9-7c15-45fd-be75-a9f83d22971b" />


Pay attention to any special requests such as  a number requesting a 3v3 or 4v4:

<img width="60" height="45" alt="3" src="https://github.com/user-attachments/assets/677a933d-3152-4eb0-b254-056ad002f6c8" />

(This is a *request* so not against the rules to race 5v3 for example, but it is considered good practice and within the spirit of fair competition, to accommodate such requests.)


An open Auction Offer will show you the time ‘window’ that the team is offering to start the fixture:

<img width="411" height="280" alt="start_time" src="https://github.com/user-attachments/assets/2ec6fb2f-74ec-49de-901e-c8cbfeee400e" />


Click ‘Accept Offer’ and then you can specify the start time within that window before it creates the Fixture:

<img width="340" height="250" alt="accepting" src="https://github.com/user-attachments/assets/a8bdfe0e-56ac-4b30-98ec-a64bb8fda6e7" />

Accepting an offer is a **commitment to race** and cannot be cancelled later.

If you don’t see an appropriate offer available, you can create your own to publish:

Note that Offers have to be further than 24 hours in future from the point of creation otherwise the system removes them - to assume 2 teams won’t have time to both find 5 riders, choose a course, create the event and get everyone signed up in time. (If you want a race within 24 hours, you need to use the Discord method).

Go to your team [dashboard page](https://ladder.cycleracing.club/dashboard) and scroll down to Availability Auctions. Here you can click ‘+Create New Auction Offer’.

Check your timezone is shown correctly, select the date you want to race, and a time window for the race start e.g. 19:00 - 19:30.
The system will show the local time, and the UTC time for the Auction.
Use the buttons to make any special *requests* such as 3v3, 4v4, or steering off.

<img width="400" height="380" alt="new_offer" src="https://github.com/user-attachments/assets/6165b5b4-f5bf-422f-99b1-1201fbe93f6b" />

To finish, click Cancel to cancel, or to publish - either click ‘+Create Auction Offer’ for a one off offer, or ‘Create Repeat Weekly’ if you want to offer the same slot every week.

Please remember that if another team accepts an offer then it is a commitment to race - you cannot cancel later because you forgot to delete an automatic recurring offer! The fixture would have to be re-arranged or the team unable to race would have to Forfeit - counting as a strike against the team.

## Making A Challenge Manually (via Discord/Website)

The challenging team are responsible for most aspects of race setup, undertaking all steps below. Teams can challenge another team no more than 7 places above them in the team ladder. Teams may challenge others of a higher rank as long as they are within 7 places. Challenges can be made up to a week in advance.

Women's teams can challenge any team within range globally (mixed or women’s), but may only be challenged by other women's teams.

The preferred method of creating a challenge is using the Availability Auction feature, though the “old” way of organising is still summarised below as a backup.

### Via Discord / Website ‘Challenge’ Method

1. In the [#race-organisation Discord channel](https://discordapp.com/channels/928942633844355122/1075443165928103966) (please navigate to the one for your specific region), create a New Post, and @ tag the captain of the opposing team you wish to challenge and here you can start any discussion on the date and time. Teams being challenged have 24 hours to respond to the challenge. Note: Please refrain from challenging multiple teams for the same time and date to "hedge your bets", it's ok to enquire about availability of more than one team at a time but once you've started the process of making a challenge it should be with a single team.

<img width="400" height="170" alt="image(2)" src="https://github.com/user-attachments/assets/9cd90733-acd5-4d8f-8400-4aa218b29533" />

2. Navigate to the league view in the ladder site and hit the blue challenge button.
3. The system will ask that you to check;
    1. You have approached this team on discord to agree a fixture?
    2. Ensured you have the riders to fulfil this race?

    Click “OK”, this will prompt you to propose a day, time and steering on/off, and then click the ‘Challenge’ button, after which it will send the challenge to the opposing captain.

4. Once the challenge has been formally accepted, the challenging team then have 36 hours to confirm their course choice (this is deliberately done after agreeing time and date, to stop the other team declining on the basis that the just don’t like the course). If the challenging team fail to propose a course within 36 hours then it will flip to the opposition to make the choice.
5. The challenging captain can then complete the Route Selection and Powerup Selection
before clicking Create Event.

<img width="600" height="300" alt="Route_Selection" src="https://github.com/user-attachments/assets/563638c3-a110-4552-bf5d-075d04e11ce1" />

7. This will instantly and automatically create the Zwift Event Link - which the captain should then share the link with the opposition Captain in the Discord thread, and with the riders of their own team who will be racing.
8. Any change requests should use the Change Event button on the Fixture page (only the team who made the original course selection will see this button option available).

---

### Steering Choice (as of May 2025)

As some of you are aware, we have been developing a method to allow the potential for "steering disabled" races.

1. During the challenge creation you will now have the choice to disable steering.
2. If you choose to disable steering you will lost the route and powerup pick, these are given to your opponents instead.
3. Captains will not know before accepting a challenge if it is "steering" or "no steering", and it is ***not*** grounds to refuse or cancel a challenge.
4. The same is true for auctions, during the offer you can choose "steering off" alongside the *request* for numbers of riders.
5. Once the Fixture is in place, the Steering Disabled icon will be visible (before the course and PU’s are chosen):

<img width="750" height="430" alt="Steering_Off" src="https://github.com/user-attachments/assets/7d7b12ef-db6a-4069-9669-a242789732fa" />

Note that at the time of release, it has passed on only the most basic testing and may be withdrawn at any stage.

---

## Accepting A Challenge

The preferred method of creating and accepting a challenge is using the “[availability auction](Club%20Ladder%20Race%20Book%20402167d503d080648570cb89af896829.md)” feature, though the “old” way of organising is still summarised below as a backup.

[https://youtube.com/shorts/UedGJrZ3aus?si=Y0ToRJbcKBpx13jp](https://youtube.com/shorts/UedGJrZ3aus?si=Y0ToRJbcKBpx13jp)

1. Ensure your team captain has joined and is monitoring [#race-organisation Discord](https://discord.gg/NZuedrjf9V).
2. Once a challenge has been made by another team, respond to accept or propose a new time within 36 hours of a challenge being made.

  <img width="300" height="270" alt="image(4)" src="https://github.com/user-attachments/assets/6eb7f41e-2e7a-4309-bb9b-d60b05e712e0" />

3. Once a challenge has been accepted, the challenging captain will confirm their course choice within 36 hours of the challenge being made, and then provide you with race links, you should distribute these to your team.
4. If you have any concerns with any of this please raise with the other captain in the first instance, any issues can be escalated to [#ladder-captains-race-control](https://discordapp.com/channels/928942633844355122/941419628922548274).

## Changing Race Event Details

Event creation has transitioned from a manual process to something a bit more automated, meaning you are able to receive an event ID back within a few moments rather than waiting on an e-mail confirmation.
**Note - event changes cannot be made within 60 minutes of the race start because this is prevented by Zwift.**

### Using the “Change Event” Button.

When viewing the fixture page on the Club Ladder website there is a “Change Event” button for the team which specified the course setup, the “home” team:

<img width="200" height="30" alt="2026-03-05_09-24 58" src="https://github.com/user-attachments/assets/a5d650f0-4ecd-45ec-a7ec-5f0d4d9a39c0" />

This will bring up a dialogue box for you to request changes:

<img width="250" height="380" alt="2026-03-05_09-25 10" src="https://github.com/user-attachments/assets/a917fab9-8ecb-43d2-95e5-663286bcaee6" />

Once submitted, the Club Ladder bot will create a message in the [🚴🏿ladder-event-changes](https://discord.com/channels/928942633844355122/1327608550200967268) channel on the Club Ladder discord server.

<img width="400" height="210" alt="2026-03-05_09-25 28" src="https://github.com/user-attachments/assets/6787c6c6-f553-4b15-9b64-9a922ca5ed27" />

At least one Captain/Vice-Captain from each team should approve the change on Discord by clicking the blue check mark (☑️ ) reaction.

When an admin has completed the change they will add a green check mark ( ✅ )

*Note : it may take a while for the system to re-scan the event details after any change, there may be a delay in the appearance on the website, but you can check Zwift or Zwift companion to confirm the changes were made correctly*

### Make A Request Via Discord

If an event needs a change (start time, course choice, course distance / number of laps etc.) then you can post any change requests in the new **⁠[🚴🏿ladder-event-changes](https://discord.com/channels/928942633844355122/1327608550200967268)** .

You **must** include;

- **The link to the ladder website fixture you want to change**

    e.g. "[https://ladder.cycleracing.club/fixture/3003](https://ladder.cycleracing.club/fixture/3003)"

- **A link to the discord thread where the opposing team have agreed to the change**

    (Required for time/date changes and route changes outside normal guidance)

- **The actual change you want**

    All times should be submitted in UTC time zone format

## Backup Clubs Process

This guide summarises how to create an event using the Zwift Clubs functionality in companion app. This can be used as a backup only when the Ladder Website is unable to create an event (this would be announced on Discord).

1. Create the event within your Zwift club in companion app, ensuring race results are on, late join off, and non-club members are able to participate.

    [](https://lh7-us.googleusercontent.com/d3n52_yXoELYQ9srETd9Q_RDiYDPKbUmw_M2JrfZs7ZsTH4bons-qL7GA29pKwgXobai3LdK2d9AtN8WYyeQUy10dDZSXfzkFlAFE-XQvTXfUk2HcHfY18hJj_wQgq_z8jgcX9kBRFpyugW6)

2. Races must be created using a consistent format: “Club ladder <fixture id>” The fixture ID can be found in the URL of the race on the ladder site.

    ![Untitled](Untitled%204.png)

3. Copy the “share event” link and add it to the system under the appropriate fixture and share with the opposing captain.

*Note: Certain limitations exist on course choices within Clubs, and it is not possible to dictate specific power ups (or try to turn steering off).*

## Sticky Watt/Equipment Analysis

1. Where a sticky watts flag is given, race control will still check that it is not a false flag, if the DQ remains 24 hours after race finish, you can assume it is correct.
2. If you'd like to investigate any possible device issues, first ask your rider to locate their log files for the ride in question - https://support.zwift.com/locating-log-files-BykKO63fr
3. Use Zwiftalizer to analyse these files to spot common device issues, dropouts of connections are particularly common causes of sticky periods. [Zwiftalizer](https://zwiftalizer.com/)

Zwiftalizer provides a range of guides and tips to help you from uploading files, to analysis and resolving issues, so we would ask captains use their site rather than asking race control, who will likely just point you towards their help pages anyway.
Zwiftalizer Help: [https://zwiftalizer.com/help](https://zwiftalizer.com/help)
Zwiftalizer Video Guides: [https://www.youtube.com/@zwiftalizer](https://www.youtube.com/@zwiftalizer)

## 🎲Rider Spot Check

A random sample of riders will be flagged every week to check equipment complies with the ladder rules - where a rider is selected for random 🎲 Spot Check, they have **72 hours** to provide the necessary verification, either directly themselves or via the captain.
Evidence should be submitted via the rider’s Verification Portal.

1. If a rider is randomly selected for spot check you will see this notified on the results page, the team admin page, the rider profile page and the captain will receive an email notification (if they’ve opted in to emails). The notification on results page is signified by a small dice.

    <img width="250" height="80" alt="1000035381" src="https://github.com/user-attachments/assets/e0fa7309-48ab-45ed-aff8-3cd142592039" />

    2. First rider should locate their <u>**LOG**</u> files for the ride in question (note: It is LOG files we need, not FIT files)  [https://support.zwift.com/locating-log-files-BykKO63fr](https://support.zwift.com/locating-log-files-BykKO63fr)
3. (Preferred), the rider should upload their log file to [Zwiftalizer](https://zwiftalizer.com/).
    1. Note that Zwiftalizer now only allows 5 free uses if you register an account.

        If you no longer have any free uses available, please contact the @Club Ladder Race Committee on Discord via your captain, to discuss how to proceed.

4. Go to the [rider spot check page](https://ladder.cycleracing.club/spotCheck) OR on the rider profile page select “upload evidence”.

<img width="200" height="110" alt="image 3" src="https://github.com/user-attachments/assets/bdd8541d-c26a-405a-b689-2d4c49669861" />
<img width="220" height="100" alt="image 4" src="https://github.com/user-attachments/assets/1cbb0869-5b1b-472b-a8d1-7c251ae351b0" />

1. Input the riders Zwift ID (this will not be requested if you are submitting directly from their profile).

<img width="330" height="110" alt="image 5" src="https://github.com/user-attachments/assets/c56ca82d-72a5-4ac9-8ca5-7a051e7f16db" />

1. Upload the necessary details. It is preferred that you give us a Zwiftalizer link, though you may also give us the log file directly.

<img width="200" height="150" alt="image 6" src="https://github.com/user-attachments/assets/6a921e4e-44d0-4f69-ac03-b5dd3a85a059" />

1. Once submitted, race control will review within 72 hours. If you don’t hear anything from us within this time, all is well. If we need anything more, like analysis of a further ride, then we’ll get in touch via the team captain.

## 🌍 World Class Verification Process

The following steps are only required in an instance where the rider has been explicitly requested by race control to undertake verification. If flagged for verification, a rider has 14 days to complete the process, during which they may continue racing.
A rider will be immediately suspended from the ladder if they:

- Fail a verification attempt
- Refuse to verify

A rider who fails a verification attempt during the 14-day window *may* be invited to re-attempt within that 14 day window, at the discretion of Race Control e.g. if due to a minor technical fault in one of the steps carried out.
Each failed verification submission will be recorded as a Major Infringement - see [Infringement Penalties](Club%20Ladder%20Race%20Book%20402167d503d080648570cb89af896829.md) for full details.
Suspension is lifted only upon successful verification.

If the 14-day window expires without successful verification, the following cooling periods apply before re-attempts are permitted, if invited to do so:
An initial 7-day period during which Race Control will not review the case.
Each subsequent failed re-attempt will be recorded as a further Major Infringement, and doubles the cooling period — 14 days, then 28 days, then 56 days, and so on.

## <u>Verification Requirements:</u>

### Provided via Rider Verification Portal on ladder website.<br>They have 14 days to do so.
1. [Weight verification video](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#weigh-in-verification-process).
2. A link to their Strava profile, and if Private - accept race control request to follow on Strava.
3. A log file for both the activity in question *and* from the verification activity, both uploaded for review by following the [Rider Spot Check](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#rider-spot-check) process.
4. One of the following which show capability at least at the level shown in the flagged event. These are listed in order of preference i.e. if selecting indoor verification test, a reason must be given why an outdoor test cannot be completed:
    1. Dual recording of the event in question, with duals uploaded to Zwiftpower, original fit files from both devices provided to race control and photo/screenshots provided of Trainer & Power Meter Serial Numbers & Firmware Version.
    2. Verified ZADA (or similar, eg Mywhoosh verification) test within the last 12 months- Please provide a copy of the test, confirmation of receipt from the governing body and evidence of participation in the verified event (ZGP, World Championships etc.).
    3. FIT files of the rider’s [best efforts outdoors](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#outdoor-power-verification) for the duration flagged (i.e. if you’ve been flagged for 5m, provide 5m data), link to effort on Strava and original FIT files provided directly to race control. These can be historical best efforts within the last 12 months or done specifically for the purposes of verification.
    4. In an instance of a rider not being able to verify outdoors, an indoor power test with their [best efforts over the required duration - dual recorded on Zwift](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#in-game-power-verification).

### Weigh In Verification Process

The full protocol for a rider measuring their weight is as follows.

Have someone else film for you, or, film yourself using a mirror so that you are visible throughout the video.

### Before starting the test

1. Set up scales suitable for measuring body weight in the middle of a room on a hard, even surface, with nothing nearby to hold on to.
2. Find a solid heavy object (approx 10kg) that you can comfortably carry. Object must clearly indicate the mass of the object (e.g., “10kg” printed on the face of a kettlebell).
3. Make sure you are wearing sports/cycling shorts and a jersey.

### During the test

1. Start recording a video on any device; for example, a cell phone
2. Show your face on the video.
3. Show yourself performing a live internet search for the current time and date, and the results that it gives. You must clearly show the URL of the website and refresh the webpage so it is clear that the time and date are current. Screenshots of mobile phone clocks or computer desktop clocks will not be accepted.
4. Show the scales.
5. Zero the scales and show the zero reading.
6. Show the portion of the object(s) showing the mass of the object (e.g., label or printing on the object).
7. Place the heavy object(s) weight on the scales and show the reading. Zoom in so that the reading is clear on the video.
8. Take the object(s) off and show the reading.
9. Pick up the scale and turn it over to show that there is nothing on the underside of the scale or on the floor. This must be shown clearly on the video.
10. Place the scale back on the floor approximately 30cm away from the previous location.
11.  Stand on the scales yourself (without the weight) and show the reading. Zoom in so that the reading is clear on the video.
12. Take yourself off and show the zero reading.
13. Stand on the scales with the object and show the reading. Zoom in so that the reading is clear on the video.
14. Take yourself off and show the zero reading.
15. Stop recording.

### After the test

1. Upload as an unlisted video to YouTube and share it with race control in the LADA discord thread, or share the file directly by uploading into Discord.
2. Weight as shown in weight recording video must be the same weight as in game for the race being verified (+- reasonable adjustment for any time which has passed since the event).
3. After race control have confirmed the weigh in video is approved, you may delete the video if you wish.

### Outdoor Power Verification

This may be done specifically for the purposes of verification, or be a previous ride provided the ride is recorded in such a way that meets the necessary criteria. It may also be from multiple different rides if different power durations are being requested (i.e. send us 1m verification from one ride and 20m verification from another)

### Test Details

1. A link to the rider’s public Strava data.
2. Rides must be conducted on a significant gradient (5% or more) and record both power and heart rate data.
3. Files may be from different rides, but all must have been made within the last 12 months.
4. Rides and effort can not be clipped/altered.
5. If the rider is located in a region where a longer hill is not accessible, a flat effort will be accepted however for the shorter durations we would highly recommend this is done on a closed circuit for safety reasons.
6. Ensure you are appropriately rested, hydrated and fed to do maximal efforts over the time periods requested.
7. The test is composed of an effort over the power duration requested by race control, this will vary depending on your individual request. It is important that you try and achieve the best possible power output for the entire duration of each effort.
8. For any effort of 2+ minutes you will need to pace yourself to produce your maximal power output for that specific duration. In other words you do not want to “fade out” significantly in the second half of the effort. The efforts can be completed seated or standing or a combination out of both.
9. For efforts of 1 minutes or under, you will need to do an all out or near all out effort, no need to pace yourself. Again, seated or standing is fine.

### After the test

1. Download the original FIT files from your recording device, or if you are sending historic efforts and don’t have the original fit files you can [download these from Strava](https://support.strava.com/hc/en-us/articles/216918437-Exporting-your-Data-and-Bulk-Export). Clearly label them as to which device they came from and send them to race control via Discord.
2. Collect details of  make, model, firmware, serial number and calibration information, slope number or calibration factor for your power meter and a photo of the hardware used. Send this to race control via Discord.

### In Game Power Verification

In an instance where a rider does not ride outside, they can provide dual recorded verification from in game, using a secondary Power Meter device. This may be done specifically for the purposes of verification, or be a previous ride provided the ride is recorded in such a way that meets the following criteria.

### Before Starting

1. Setup a camera to simultaneously show you, your bicycle, your trainer and the Zwift screen throughout. This can be done with a webcam and streaming software (such as Streamlabs OBS), or a mobile device.

### During the test

1. Start streaming from the point of login. In particular, your stream must include the pairing screen and selection of the smart trainer (or smart bike), cadence sensor, and heart rate monitor. If these are automatically selected on logging in, then you must unselect them, and then reselect them.
2. Setup Zwift to record the power from the trainer, and a separate cycle computer to record from a separate power meter (usually, power cranks / pedals).
3. Setup both Zwift and the cycle computer to record cadence and heart rate, but these can be from the same sensor for each.
4. Set the “Power Display” option in the Zwift settings menu to “instant” (i.e., not “3 second average”).
5. Set the cycle computer to record at 1 second intervals.
6. Set the Trainer Difficulty to a minimum at 50% for the full duration of the test.
7. Ride a 10-20 minute warm up of your own choosing.
8. Perform spindown of trainer (if applicable) and calibrate zero-offset of power meter after the warmup (follow spindown and zero-offset calibration instructions below).

### Test details

1. Ensure you are appropriately rested, hydrated and fed to do maximal efforts over the time periods requested.
2. The test is composed of an effort over the power duration requested by race control, this will vary depending on your individual request. It is important that you try and achieve the best possible power output for the entire duration of each effort.
3. For any effort of 2+ minutes you will need to pace yourself to produce your maximal power output for that specific duration. In other words you do not want to “fade out” significantly in the second half of the effort. The efforts can be completed seated or standing or a combination out of both.
4. For efforts of 1 minutes or under, you will need to do an all out or near all out effort, no need to pace yourself. Again, seated or standing is fine.

### After the test

1. Upload as an unlisted video to YouTube and share it with race control in the LADA discord thread, or share the file directly by uploading into Discord.
2. Download the original [FIT files from Zwift](https://support.zwift.com/en_us/your-activity-history-and-fit-files-SJbHywdNH) and from your GPS device, clearly label them as to which device they came from and send them to race control via Discord.
3. After race control have confirmed the verification is approved, you may delete the video if you wish.

## Add/Change A Captain or Team Admin (Vice Captain)

### **How to change Captain of a Ladder Team**

1. New Captains/VCs needs to make themselves known on discord (in **⁠[new-rider-intros](https://discord.com/channels/928942633844355122/928942634305720380)**) , so as to be given Captains access - including updating their Discord Server nickname to include both Club and Team as per the welcome instruction.
2. A new Captain or Vice Captain will first need to register a Captain/VC account on the ladder website [https://ladder.cycleracing.club/signup](https://ladder.cycleracing.club/signup)
    1. If a user has an existing <u>Rider</u> account for the website, this can be upgraded to a Captain / Vice Captain account by using the [Captain/Vice Captain Sign-in](https://ladder.cycleracing.club/signin). Use your existing Rider login (Google or Discord), to upgrade their account.
    Creating a new account via a different login method only created duplicate accounts).
3. Existing captain goes to their team management page and shares that page URL link with the new captain, before clicking the ‘Resign Captaincy’ button.
4. Previous captain updates their Discord Server nickname to remove Team name.
5. New captain follows the link to the team management page and clicks the ‘Claim Captaincy’ button.

---

### **How to add a Team Admin (Vice Captain)**

1. You can have multiple Team Admins (Vice Captains) of a team.
2. To add a Team Admin Vice Captain), they first need to join and make themselves known on discord (in **⁠**[new-rider-intros](https://discord.com/channels/928942633844355122/928942634305720380) ) , so as to be given Vice Captains role - including updating their Discord Server nickname to include both Club and Team as per the welcome instruction.
    1. If a user has an existing <u>Rider</u> account for the website, this can be upgraded to a Captain / Vice Captain account by using the [Captain/Vice Captain Sign-in](https://ladder.cycleracing.club/signin). Use your existing Rider login (Google or Discord), to upgrade their account.
    Creating a new account via a different login method only created duplicate accounts).
3. New Vice Captain needs to register a VC account on ladder website [https://ladder.cycleracing.club/signup](https://ladder.cycleracing.club/signup)
4. Existing captain goes to their team management page , and should use the Change Team Admins button to assign a Team Admin (Vice Captain)

<img width="300" height="80" alt="Change_Team_Admins" src="https://github.com/user-attachments/assets/b4784100-59de-4057-af69-739b0eb925b6" />

5. In the Edit Admins menu, use the drop-down menu and select your Vice Captain.

    Note that the list of admins is drag-able, with the top placed name being assigned as Captain.

6. The list will be of anyone registered as captain/vc on the Ladder website, *and* who is part of the same ZP club the team was attached to. Otherwise they don't appear.

    (Note - we get the Club data from zwiftracing so you need to do an activity that zwiftracing will recognise, for it to pass through to our system)

7. If they do not appear in this list, please double check that they have completed step #2 above, and that they are registered to the same Zwift Power club that the Ladder team is attached to, as their <u>primary</u> club.

- Note that resigning your Captain or Vice Captain account on the ladder website, *might* automatically remove your corresponding role on Discord (if you have Discord verified). If you require reassigning then you will need to message a Club Committee member asking them to re-assign it to you.

## Bug Reporting

1. Please report any bugs via the appropriate Discord channel [🐞 bug-reporting](https://discord.com/channels/928942633844355122/1117086488597897226/1186701415809286194)
2. This channel will only accept new messages that include a http link (either to fixture, team, or rider.) Others are automatically deleted. This is done to help speed up support time by the race committee - “help us to help you!”
3. When reporting a bug, the more information we have the quicker we can assist in helping, please try to report with information such as the following :-
- <u>Title</u>: Keep it brief and use correct terms. A best practice is to include the name of the feature where you found an issue. A good example could be 'CHALLENGE - Unable to challenge [XXX] team'.
- <u>Description/summary</u>: If you feel the name is not sufficient, explain the bug in a few words.
- <u>Environment</u>: Depending on your device, browser, operating system. Your user account, team you manage, are you vice or captain?
- <u>Source URL</u>: Make it easy for everyone to spot the problem by including the URL of the page where you found the bug. Links to riders, fixtures, results, etc.
- <u>Visual proof</u>: A picture is worth a thousand words. Although it might not be enough, a visual element like a screenshot or a video will help your developers understand the problem better and faster.
- <u>Steps to reproduce</u>: A screenshot is a proof that you had a problem, but keep in mind that your developer might not be able to reproduce the bug. Make sure to describe, with as much detail as possible, the steps you took before you encountered the bug.
- <u>Expected result vs. actual result</u>: Explain what results you expected - be as specific as possible. Just saying "the app doesn’t work as expected" is not useful. It's also helpful to describe what you actually experienced.

## Purge A Refused Data Consent<br>(legacy - see [Linking / Unlinking with Zwift (new data consent)](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#linking--unlinking-with-zwift-new-data-consent))

1. In order to create race results and undertake the performance verification necessary for fair racing we require to collect and store some of your data, we need your consent to do this. This data includes any publicly available personal and performance data on your Zwift, ZwiftPower or ZwiftRacing profile. Without your consent unfortunately you will be unable to participate in any ladder events. If you’d like to find out more information about the data we collect and how we use it, please refer to our [privacy policy](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#privacy--cookie-policy).

2.            ***Refusing consent will mean you cannot ride in the Ladder series.***

3. Consent must be given by a rider, and not on their behalf, and can be given at [https://ladder.cycleracing.club/riderConsent](https://ladder.cycleracing.club/riderConsent)
4. If a rider has rejected Data Consent and later wishes to join the ladder, an Amin must be contacted to change / purge the Data Consent.

    <img width="300" height="480" alt="bfb00937-bf69-4855-8033-a0ac51513680" src="https://github.com/user-attachments/assets/3232f217-0a24-42b4-8820-e1fd167e19d7" />

5. Use the [#ladder-captains-race-control](https://discord.com/channels/928942633844355122/941419628922548274) channel on Discord, and provide the rider ID number, and tag @ClubLadderRaceCommittee asking nicely for them to Purge data consent so that the riders can then resubmit their consent.

# 📷 Glossary

- (On results page), rider has been randomly selected for a [🎲Rider Spot Check](https://github.com/gazhay/rules-clubladder/edit/main/docs/index.md#rider-spot-check).

    <img width="75" height="90" alt="image 7" src="https://github.com/user-attachments/assets/add837bf-18fe-46a2-b11e-04bd1f5f5a93" />

- This padlock icon denotes that the user *preference* is Private activities, and serves as a reminder for captains to ask the rider to save Ladder races as a Public Activity on Zwift.

    <img width="75" height="80" alt="image 8" src="https://github.com/user-attachments/assets/f70fb175-640a-4900-a22a-5ba90420d6d1" />

- Rider / roster refresh - icon should only be visible during an open Transfer Window (if a new rider added to roster shows errors, try this manual refresh in the first instance).

    <img width="46" height="47" alt="image 9" src="https://github.com/user-attachments/assets/58236eb5-1e73-4a3c-a67a-8e421f050b58" />  

- (Legacy - Rider has no valid 30day rank on [https://www.zwiftracing.app](https://www.zwiftracing.app/))

    <img width="68" height="35" alt="image 10" src="https://github.com/user-attachments/assets/c91b5dd4-6213-4611-b8e1-16badacb4eed" />

- Team is in a ‘Zombie’ state, and can be bypassed in challenges.

    <img width="37" height="34" alt="image 11" src="https://github.com/user-attachments/assets/a71917d6-589d-456f-aefb-8b738636efd0" />

- Team is in a ‘dead’ state, and will be removed from the ladder.

    <img width="53" height="36" alt="image 12" src="https://github.com/user-attachments/assets/9536737b-ff6c-4c6a-9ce0-9a9f4e162692" />

- ‘Cancel’ on a fixture not yet accepted - this cancels the fixture, nothing changes.

    <img width="419" height="225" alt="image 13" src="https://github.com/user-attachments/assets/7e8088cf-d309-4cc7-ab69-43fdb7c22b1e" />

- (Displayed on captains team admin page). Represents the ranks that may currently be added to the team, this will change based on the riders currently on the roster. Yellow shaded rank represents the median rank in the team and riders can be added +/- 1 rank from this.

    <img width="171" height="106" alt="image 14" src="https://github.com/user-attachments/assets/e499ed7a-9c8a-4c4d-af64-7997e5c49e24" />

- If the challenging team fail to propose a course within 36 hours then it will flip to the opposition to make the choice.

    <img width="168" height="38" alt="image 15" src="https://github.com/user-attachments/assets/5f3f9783-a86e-4cd0-a1e0-081fd0e6ff31" />

- W= Won challenge, L= Lost challenge, D= Defended challenge (i.e. you were the higher ranked team and you defended a challenge from the team below).

    <img width="122" height="31" alt="image 16" src="https://github.com/user-attachments/assets/f5d8605c-663c-4038-8e0e-b1667dfc1221" />

- This indicates a rides has been given a [shadow ban](https://forums.zwift.com/t/riders-cant-see-me-in-race/627466) directly from Zwift. The rider would need to contact Zwift directly to find out what the issue is.
Any shadow banned riders are auto-banned at Ladder, but even if they were not, if they turn up to a race they wouldn't appear in the results anyway so there is nothing we can do. The ladder ban is more of a notification for the rider to go and ask Zwift about the ban.

    <img width="450" height="110" alt="image 17" src="https://github.com/user-attachments/assets/a2816913-510a-4d10-a290-1db873e86ed6" />

- <u>**Once the challenge has been Accepted:**</u>

    ‘Random’ will generate a random course choice for you.

    ‘Surrender course section’ flips the decision to the opposing team to be able to choose.

    ‘Forfeit’ will forfeit the entire fixture (note this is ***not*** a Cancellation - the forfeiting team will “lose” the fixture).

    <img width="393" height="358" alt="image 18" src="https://github.com/user-attachments/assets/e3654aec-6cae-4945-bb0e-d5ccd9c10715" />

- <u>**Auction Offer Symbols:**</u>

    A number ‘3’ in Hexagon indicates the team are requesting a 3v3 in their offer.
    Note this is a *request.*

    <img width="37" height="35" alt="image 19" src="https://github.com/user-attachments/assets/b9d18844-602a-409a-a578-42fa13caab2a" />

    A number ‘4’ in Hexagon indicates the team are requesting a 4v4 in their offer.
    Note this is a *request.*

    <img width="34" height="32" alt="image 20" src="https://github.com/user-attachments/assets/dbed7189-5c79-4b86-ae59-9c350ff7eaaf" />

    A number ‘5’ in Hexagon indicates a standard 5v5 offer.

    <img width="36" height="31" alt="image 21" src="https://github.com/user-attachments/assets/479faa8f-49ed-4428-b978-110bc25f09c3" />

- The rider on a roster will have a ’Z’ symbol next to their name if they have Linked their Zwift account to Ladder (authorised Data Consent).

    <img width="261" height="40" alt="Rider_linked_Z" src="https://github.com/user-attachments/assets/86787620-1693-4c07-9cda-bfbde0b36151" />

- The rider on a roster will have a warning triangle ⚠ symbol next to their name if they have unlinked their Zwift account from Ladder. This means they are not eligible to race.

    <img width="91" height="61" alt="image 22" src="https://github.com/user-attachments/assets/6f470170-c008-48c6-973e-325e1d02acef" />

# 📜 Changelog

All notable changes to the rulebook will be documented here.

## TBC

- New rulebook published.


# Privacy & Cookie Policy

This privacy notice tells you what to expect us to do with your personal information on the club ladder site found at [cycleracing.club](http://cycleracing.club).

## Our contact details

privacy@cycleracing.club

## What information we collect, use, and why

We collect or use the following information to create race results and undertake performance verification necessary for fair racing:

- Names and contact details, provided to us when you create an account.
- Upon completion of each ladder race we collect account profile information, race performance and basic biometric information as made available on your public profile on Zwift, Zwiftpower & ZwiftRacing.

## Lawful basis

Our lawful basis for collecting or using personal information to create race results and undertake performance verification are:

- Your explicit consent prior to participating in any event.

## Where we get personal information from

- You directly, on creation of an account
- Third parties: Zwift, Zwiftpower, ZwiftRacing.

## How long we keep information

We only process new information upon completion of each ladder race.

We will keep your historical information for as long as necessary to create or hold a history of event results.

## **Children**

We do not knowingly collect or use personal data from children under the age at which they are able to give self consent in their given country, our default minimum age is 16 years old however if you wish to verify your residency in a country with a lower age of self consent for data processing then you may contact us at zwiftclubladder@gmail.com. If we learn that we have unknowingly collected personal data from a child under 16 years of age, the personal data will be deleted as soon as possible. If a child under 16 years of age has provided us with personal data their parent or guardian may contact our privacy officer.

## Cookie Policy

A cookie is a small file, stored on a user's hard drive by a website. Its purpose is to collect data relating to the user's browsing habits. You can choose to be notified each time a cookie is transmitted. You can also choose to disable cookies entirely in your internet browser, but this may decrease the quality of your user experience.

We use the following functional cookies on our site:

**Cookie Key**: connect.ssid

**Expiration**: Session

**Description**: This cookie is used for session management in web applications allowing the server to maintain user session-state across multiple requests

## Sharing information outside the UK

Where necessary, we may transfer personal information outside of the UK. When doing so, we comply with the UK GDPR, making sure appropriate safeguards are in place. Please contact us for more information.

## Your data protection rights

Under data protection law, you have rights including:

**Your right of access** - You have the right to ask us for copies of your personal data.

**Your right to rectification** - You have the right to ask us to rectify personal data you think is inaccurate. You also have the right to ask us to complete information you think is incomplete.

**Your right to erasure** - You have the right to ask us to erase your personal data in certain circumstances.

**Your right to restriction of processing** - You have the right to ask us to restrict the processing of your personal data in certain circumstances.

**Your right to object to processing** - You have the right to object to the processing of your personal data in certain circumstances.

**Your right to data portability** - You have the right to ask that we transfer the personal data you gave us to another organisation, or to you, in certain circumstances.

**Your right to withdraw consent** – When we use consent as our lawful basis you have the right to withdraw your consent.

You don’t usually need to pay a fee to exercise your rights. If you make a request, we have one calendar month to respond to you.

To make a data protection rights request, please contact us using the contact details at the top of this privacy notice.

### How to complain

If you have any concerns about our use of your personal data, you can make a complaint to us using the contact details at the top of this privacy notice.

If you remain unhappy with how we’ve used your data after raising a complaint with us, you can also complain to the ICO.

The ICO’s address:

Information Commissioner’s Office

Wycliffe House

Water Lane

Wilmslow

Cheshire

SK9 5AF

Helpline number: 0303 123 1113

Website: [https://www.ico.org.uk/make-a-complaint](https://ico.org.uk/make-a-complaint/)

## Last updated

27 May 2024
