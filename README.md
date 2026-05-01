# Faza

Personal app for capturing what you like across life—categories, entries, tags, and (later) social sharing with friends. Early stage: product and learning-first; the codebase will grow in small steps.

## Vision (high level)

- **Private by default**; sharing later with friend lists (similar in spirit to “close friends”).
- **Flexible categories** and **entries** (general template first, specialized templates later for places, foods, brands, items, activities, songs, movies).
- **Search- and tags-first** recall; structured forms per category.
- **Swipe backfill** from external catalogs (e.g. movies) to add things from the past—planned after a solid core capture flow.

## Near-term MVP (simple slice)

1. **Create account** (sign up / sign in).
2. **Categories** — create and list.
3. **Items** — create and list within a category.

Social (friends, lists, feeds) comes **after** this core works on device.

## Planned stack

- **Client:** iOS, Swift, SwiftUI (learning-friendly).
- **Backend:** managed BaaS (e.g. Supabase or Firebase)—auth plus database for categories and items, with row-level security so each user only sees their own data.

## Repository status

This repo currently holds **project direction and documentation**. Application source will be added incrementally (e.g. Xcode project or Swift package layout) as implementation starts.

## License

Not specified yet. Add a `LICENSE` file when you decide how you want to share this project.
