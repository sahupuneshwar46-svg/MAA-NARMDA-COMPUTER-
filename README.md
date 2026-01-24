<style>
    .gallery-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 15px;
        padding: 20px;
        max-width: 1100px;
        margin: 0 auto;
    }
    .gallery-item {
        width: 100%;
        height: 200px;
        background-color: #ddd;
        border-radius: 10px;
        overflow: hidden;
        border: 3px solid #fff;
        box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .gallery-item img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        transition: 0.4s;
    }
    .gallery-item img:hover {
        transform: scale(1.1);
    }
</style>

<h2 class="section-title">Hamara Best Work (Gallery)</h2>
<div class="gallery-container">
    <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=400" alt="Passport Sample">
    </div>
    <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1511795409834-ef04bbd61622?q=80&w=400" alt="Wedding Sample">
    </div>
    <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1597733336794-12d05021d510?q=80&w=400" alt="Computer Work">
    </div>
    <div class="gallery-item">
        <img src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=400" alt="Studio Setup">
    </div>
</div>
