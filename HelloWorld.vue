<template>
  <div class="hello">
    <div class="main-content">
      <h1 class="title">{{ title }}</h1>
      <div class="image-container">
        <img class="artist-image" src="@/assets/sidhumoosewala.jpeg" alt="Sidhu Moosewala Image">
      </div>
      <p class="description">
        Sidhu Moosewala is a renowned Punjabi singer, songwriter, and actor known for his powerful voice and impactful lyrics.
      </p>
      <h3 class="section-title">Popular Songs</h3>
      <ul class="song-list">
        <li><a href="https://www.youtube.com/watch?v=rMQ_TUEwQEs">Just Listen</a></li>
        <li><a href="https://www.youtube.com/watch?v=Wwia571TwkU">Warning Shots</a></li>
        <li><a href="https://www.youtube.com/watch?v=YZAFd9o3RYQ">Legend</a></li>
        <!-- Add more songs with their respective YouTube links -->
      </ul>
    </div>
    <div class="sidebar">
      <h3 class="sidebar-title">Explore</h3>
      <p><a href="https://en.wikipedia.org/wiki/Sidhu_Moose_Wala" target="_blank" rel="noopener">Sidhu Moose Wala - Wikipedia</a></p>
      <p><a href="https://www.youtube.com/channel/UC9ChdqQRCaZmTCwSJ49tcbw" target="_blank" rel="noopener">Sidhu Moose Wala - YouTube Channel</a></p>
      <p><a href="https://www.instagram.com/Sidhu_MooseWala/" target="_blank" rel="noopener">Sidhu Moose Wala - Instagram</a></p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    title: String
  }
}
</script>

<style scoped>
.hello {
  display: flex;
  justify-content: space-between;
  max-width: 800px;
  margin: 0 auto;
}

.main-content {
  flex: 1;
  text-align: center;
}

.title {
  font-size: 36px;
  margin-bottom: 20px;
  color: #333;
}

.image-container {
  margin-bottom: 20px;
}

.artist-image {
  width: 100%;
  border-radius: 10px;
}

.description {
  font-size: 18px;
  color: #555;
}

.section-title {
  margin-top: 40px;
  font-size: 24px;
  color: #333;
}

.song-list {
  list-style-type: none;
  padding: 0;
}

.song-list li {
  margin-bottom: 10px;
  font-size: 16px;
  color: #666;
}

.sidebar {
  flex: 0 0 200px;
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 5px;
}

.sidebar-title {
  font-size: 18px;
  margin-bottom: 10px;
}

.sidebar a {
  color: #007bff;
  text-decoration: none;
}

.sidebar a:hover {
  text-decoration: underline;
}
</style>
