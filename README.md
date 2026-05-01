# Faza

Faza is a personal **interest tracker** (and eventually a **social discovery** layer) for everything you care about—movies, music, books, food, places, and custom categories—so your taste is not lost to time.

Memory is lossy: the album on repeat, the film you loved but cannot name, the restaurant from a trip. Faza is meant to be the **organized, searchable place** those things live, with **private-by-default** data and **friend-based sharing** added only when you are ready.

## Vision (current direction)

- **Private by default**; later: share with **named friend lists** (similar in spirit to “close friends”), not the whole world by default.
- **Flexible categories** and **entries**—start with a **general** template, then specialized flows for places, foods, brands, items, activities, songs, movies.
- **Search- and tags-first** recall; **structured forms** per category.
- **Swipe / “explore” backfill** from **external catalogs** (for example TMDB for movies) to add things from the past—**after** a solid sign-up → categories → items core.

## Near-term MVP (first code milestone)

1. **Create account** (sign up and sign in).
2. **Categories** — create and list.
3. **Items** — create and list within a category.

**Social** (friends, lists, feeds) ships **after** this core is stable on real devices.

## Planned stack (iOS-first)

| Layer | Technology |
| --- | --- |
| Client | iOS, Swift, SwiftUI |
| Backend | Managed BaaS (e.g. **Supabase** or **Firebase**) — auth + database |
| Data rules | Row-level security so each user only reads/writes their own rows |

Earlier drafts of this README mentioned React Native and a custom Node backend; the **current plan** is the table above unless that changes explicitly in the repo.

## Later roadmap (not MVP)

- Curated **browse / swipe** inside a category, powered by public APIs (movies, books, music, games, places—depending on category type).
- **Time context** on entries (“when” as a specific date or a span / phase of life).
- **Social layer**: friends, recommendations, small-group activities—staged after the personal vault works well.

## Repository status

This repo currently holds **project direction**; **application source** (Xcode project layout, etc.) will land incrementally as implementation starts.

## Contributing

Early development. Ideas and issues are welcome.

## License

Not specified yet. Add a `LICENSE` file when you decide how you want to share this project.
