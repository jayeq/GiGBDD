# Story: View rewards in Freebies Vault

**As a** user
**In order to** ensure my most recently claimed rewards (tokens) are accounted for
**I want to** see my claimed rewards in the Freebies Vault section.

## Scenario 1: History displays upon token claim.
**Given** that a user has been awarded a token.
**When** the user claims the token
**Then** the “Your History” of the “Freebies Vault” section will be displayed.

## Scenario 2: Claimed rewards displayed correctly.
**Given** that a user has claimed at least 9 tokens.
**When** they open “Your History” in the “Freebies Vault” section
**Then** they should only see thumbnails for 8 tokens
**And** those tokens’ thumbnails will be in reverse chronological order. (i.e. most recent first)

## Scenario 3: Game Slug displayed for tokens.
**Given** that a user has claimed a token
**And** the token has a game slug.
**When** they hover their cursor over the token’s thumbnail in “Your History”
**Then** the game slug should appear above the thumbnail in a quote bubble.

## Scenario 4: Tokens claimed more than once display correctly
**Given** that a user has claimed a token more than once
**And** both tokens have been claimed within the last 8 tokens claimed.
**When** they view “Your History”
**Then** they should see the token’s thumbnail for each claim
**And** those token thumbnails will be displayed in reverse chronological order.

## Scenario 5: FREESPIN tokens are displayed as such.
**Given** that a user has claimed a token from a Free Spin
**And** that token has been claimed within the last 8 tokens claimed.
**When** they view “Your History”
**Then** they should see that token’s thumbnail
**And** the FREESPIN icon will display over the thumbnail in the bottom-right.




