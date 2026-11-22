# ARIN121-Assignment3-TravelPlanner
Assignment #3 Travel Planner - Built off system instructions developed in Assignment #2

A conversational AI travel assistant that helps travellers either build a personalized itinerary or decide where to go. It is configured entirely through a system prompt (see system_prompt.md).


What It Can Do:

The assistant offers two activities through a simple menu:

Build a day-by-day itinerary: for a destination you've already chosen.
Help choose between destinations: for when you're still deciding where to go.
Using the Menu

At the start of a conversation, or whenever your request is vague (e.g., "help me plan a trip"), the assistant shows the menu. You can pick an activity in any of these ways:

By number: reply 1 or 2
By name: e.g., "destination help"
In your own words: e.g., "plan 5 days in Kyoto" starts an itinerary, and "I can't decide between Lisbon and Barcelona" starts destination help

Once you've chosen, the menu stays out of the way. You can ask to see it again or switch activities at any time, and the assistant will carry forward details you've already shared (destinations, trip length, dates, budget, interests) so you don't have to repeat yourself.


Activity 1: Build an Itinerary

Provide a destination and trip duration (required). Travel dates, budget, interests, and preferences are optional but will be used to personalize the plan.

The assistant generates a day-by-day plan with morning, afternoon, and evening activities, each with a short description. Weather-dependent or otherwise conditional activities come with a backup option. You can then refine the plan, for example by:

adding or removing a destination on a multi-stop trip (the assistant will first ask whether to change the trip length)
introducing a new budget constraint (the assistant explains what to cut and suggests low-cost alternatives)


Activity 2: Help Choose Between Destinations

A multi-turn conversation that guides you toward a decision, one question at a time:

Options: tell the assistant which destinations you're considering (or ask it to suggest some).
Priorities: share what matters most to you, such as budget, weather, food, culture, or relaxation.
Comparison: receive a side-by-side summary of the trade-offs, including honest downsides.
Concerns: raise any remaining worries or deal-breakers, which the assistant addresses directly.
Recommendation: get a clear pick tied to your priorities, which the assistant revises if you push back.

Once you've decided, the assistant offers to build an itinerary for your chosen destination using the details you've already shared.


Out-of-Scope Requests:
If you ask about something unrelated to travel planning, the assistant politely explains what it can help with and shows the menu again.
