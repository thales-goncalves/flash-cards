<script setup></script>

<template>
  <div class="card">
    <img src="../assets/card_preview.svg" />

    <main class="content">
      <ul class="tags">
        <li class="tag">Learning</li>
        <li class="tag">Javascript</li>
      </ul>
      <h3>Published 21 Dec 2023</h3>
      <h1>HTML & CSS foundations</h1>
      <p>
        These languages are the backbone of every website, defining structure,
        content, and presentation.
      </p>
    </main>

    <footer>
      <h2>Greg Hooper</h2>
    </footer>
  </div>
</template>

<style lang="scss" scoped>
.card {
  width: 384px;
  height: 522px;

  display: flex;
  align-content: center;
  flex-direction: column;
  gap: 24px;

  padding: 24px;

  border: 1px solid var(--Black, #111);
  border-radius: 20px;

  background-color: #fff;
  box-shadow: 8px 8px 0px 0px #000;
}

.content {
  display: flex;
  flex-direction: column;
  gap: 12px;

  h1 {
    font-size: 24px;
    font-style: normal;
    font-weight: 800;
    line-height: 150%;
  }

  h3 {
    font-size: 14px;
    line-height: 150%;
  }

  p {
    color: var(--Grey, #7f7f7f);

    font-size: 18px;
    font-style: normal;
    font-weight: 500;
    line-height: 150%;
  }

  .tags {
    display: flex;
    gap: 1rem;
    .tag {
      padding: 4px 12px;
      border-radius: 4px;
      background-color: $yellow;
    }
  }
}

footer {
  h2 {
    font-family: Figtree;
    font-size: 16px;
    font-style: normal;
    font-weight: 800;
  }
}
</style>
