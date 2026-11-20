# Gym Tally

A private gym accountability app for a group of four friends.

**Live:** [sharonusuanlele.github.io/gym-tally](https://sharonusuanlele.github.io/gym-tally/)

---

## How it works

- **Plan your days.** Pick at least 3 gym days a week. Plan each week by Sunday night; once the week starts it's locked.
- **Pin your gym.** Stand inside your gym and pin it with a live photo. Everyone can see each pin on a map.
- **Check in.** On a gym day, take a live photo in the app. It records the time and your location, and only counts within 200m of your gym.
- **Miss a day, pay £5.** Missed days add up automatically.
- **Win the pot.** Fewest misses each month wins, then most sessions. A tie rolls the pot over.

Season: 1 December 2026 to 31 May 2027.

## Fair play

- Live camera only, no gallery uploads
- Server side time and distance checks
- Every photo, location and gym pin is visible to the group
- An admin can reject a check in as a missed day, or approve a genuine one

## Built with

- A single `index.html` page, hosted on GitHub Pages
- [Supabase](https://supabase.com) for login, database and photo storage
- Row level security so only invited members can see anything
