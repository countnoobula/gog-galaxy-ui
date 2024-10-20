# Proposal for GOG Galaxy UI Improvements

As per a recent feedback survey I provided from in-app, I wanted to write an accompanying document detailing my thoughts.



--- 

### 1. Overview

The current overview of the page fits poorly as there is a lot of wasted space and hardly shows any data. Even when opened at a vertical resolution of 2520 (by dragging across two screens), I was able to see:

- New arrivals

- Games for you

- Additional contnet for your games

- Good Old Games (See note A)

- Explore games: {category}

Notes:

- A: It was empty and just a header, which was bad form given I had to look all the way to the right. I do have GOG games in my account, so I'm not sure why it was empty? It should be removed if empty.
- B: I feel a lot of this can be fixed by reducing the amount of negative space and improving the layout slightly.

![Overview of visibility](https://github.com/countnoobula/gog-galaxy-ui/blob/main/Current-Overview.png?raw=true)

### 2. Highlights

This is a good hero that auto-scrolls. I have no complaints, it is well structured for the image space it uses.

### 3. New Arrivals

This is where i have my main issue with the UI. I feel the space is wrongly spread. From a business/marketting perspective, I understand the need to have those be the primary header to announce their presence, however I do not feel a fully left-aligned card is the most optimal way to do this.

Here is a proposal that maintains the focus of being a new arrival with it's space dominance, but cleans up the visibility a bit.)
![Proposal - New Arrivals](https://github.com/countnoobula/gog-galaxy-ui/blob/main/Proposal-New_Arrivals-Entry.png?raw=true)

### 4. Games for you

I like the idea of how this is layed out, I think it's great. I do however feel we have wasted vertical space. I understand it's difficult to balance the varying title length for this. Perhaps moving the discount amount to the same line as the price is a good idea rather than a vertical stack.
I do think the hover filling out the discount amount is a bit inefficient. Perhaps we can rather have it constantly filled and put a currency sign at the start ($ is usually the standard).
Here is what that might look like, I'm not entirely sold on this:
![Proposal Games for you](https://github.com/countnoobula/gog-galaxy-ui/blob/main/Proposal-Games_for_you.png?raw=true)

### 5. Good Old Games

This is empty. This should not be shown unless we have something to show in it. On a 16:9 aspect ration (Ignoring ultrawide/super-ultrawide woes), this is still difficult to follow.

### 5. Additional content for your games

I love seeing DLC's! This is amazing, especially as new options become available. I do feel it needs some more info though.
![Proposal - Additional Content](https://github.com/countnoobula/gog-galaxy-ui/blob/main/Proposal-Additional_content_for_your_games.png?raw=true)

### 6. Check all games on GOG

This is a great hero at the bottom, I have no complaints for this.

### 7. Explore games: {category}

This has the same feedback as `4. Games for you`

### 8. News

This is a great scroll/feed. It could do with some improvements in layout to make it more appealing to click on. 

![News-Entry](https://raw.githubusercontent.com/countnoobula/gog-galaxy-ui/refs/heads/main/Proposal-News-Entry.png)

### 9. Check all games on GOG

This is a nice CTA at the bottom. I like it






























