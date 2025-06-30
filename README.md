# Height-Balanced Masonry Columns

Two-Column Height-Balanced Masonry Layout (Greedy Packing Algorithm)
This code snippet implements a pure CSS and JavaScript-based 2-column layout that dynamically distributes blocks to minimize vertical whitespace. Unlike standard grid or flexbox systems that align items row-wise or by count, this layout prioritizes total column height balance, ensuring a clean and aesthetic look — especially when block heights vary.

🔍 How It Works:
All content blocks are temporarily rendered off-screen to allow accurate height measurement (even if hidden).

JavaScript measures each block’s true height, including spacing.

It then uses a greedy algorithm to assign each block to the column with the lowest cumulative height.

This ensures that both columns grow together, staying as close in height as possible — minimizing leftover white space.

✅ Perfect For Scenarios Like:
     Dashboard widgets or tile-based UIs (e.g., analytics blocks)
     Portfolio or gallery layouts where items differ in size
     Blog feed layouts that auto-distribute mixed content cards
     Dynamic content feeds where block height is unknown until runtime
     Visual balance between two scroll columns for user experience

🧠 Key Features:
     Responsive-friendly foundation
     No third-party libraries needed
     Handles dynamic block heights
     Visual consistency across devices
