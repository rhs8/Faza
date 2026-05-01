# Faza

Faza is a personal interest tracker. Down the line I want it to grow into something social around discovery, but the first goal is simple: a place for the stuff you actually care about, across movies, music, books, food, places, and whatever categories you invent.

We are all swimming in information all day. Notifications, feeds, half watched videos, tabs you never close. It trains a short attention span and it makes it harder for anything to stick. I am getting older and I feel memories drifting, not always the big life moments but the small texture of what I was into at a time. Faza is my attempt to keep that texture on purpose: organized enough to find later, honest about what mattered to you, and private until you say otherwise. Sharing with friends, in a controlled way, comes after the personal side feels solid.

## What I am building toward

- Default is private. Later I want sharing with specific friend lists, not a broadcast to everyone by default.
- You make categories and add entries. Start general, then tighter flows for places, food, brands, physical items, activities, songs, movies.
- Heavy on search and tags, with structured forms per category so entries do not turn into mush.
- A swipe style flow backed by real catalogs (movies first makes sense) so you can pull things in from the past, but only after sign up, categories, and items feel good.

## First milestone

1. Create an account (sign up and sign in).
2. Categories: create them and see them listed.
3. Items: add items inside a category and list them.

Friends, lists, feeds, all of that lands after this core works on a real phone.

## Stack I am planning

- **Client:** iOS with Swift and SwiftUI (I want to learn Swift properly).
- **Backend:** a managed BaaS, probably Supabase or Firebase, for auth and a real database.
- **Rules:** row level security so a user only touches their own rows.

An older version of this README talked about React Native and a Node server. Ignore that unless this file changes again on purpose. iOS plus a BaaS is the plan now.

## Later (not the first build)

- Browse and swipe inside a category using public APIs where it fits.
- A real sense of when something mattered: a specific date or a looser span or phase of life.
- Social pieces once the personal vault feels trustworthy.

## Repo state

Right now this is mostly direction. The actual Xcode project and source will show up here as I go.

## Contributing

Still early. If you have ideas, open an issue.

## License

I have not picked one yet. When I do, there will be a `LICENSE` file in the root so it is obvious what people can do with the code.
