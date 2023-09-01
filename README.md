# Two Ways Implement Infinite Scrolling Pagination using NextJS Server Actions.

1. Setup Nextjs      
  - npx create-next-app@latest ./    
  √ Would you like to use TypeScript with this project? ... No     
  √ Would you like to use ESLint with this project? ... No    
  √ Would you like to use Tailwind CSS with this project? ... No    
  √ Would you like to use `src/` directory with this project? ... No    
  √ Use App Router (recommended)? ... Yes   
  √ Would you like to customize the default import alias? ... No    

  - next: "13.4.19" or Later   
  - next.config:   
      experimental:{   
        serverActions: true    
      },    
      images: {    
        formats: ['image/avif', 'image/webp'],     
      }   

2. Setup Mongodb (mongoose) => npm i mongoose    
  - Connect to MongoDb   
  - Models (photo)   

3. Import Data   
  - Actions => insertManyPhotos   
  - Components => InitData   
 
4. Nav + Get All Photos    
  - Actions => getAllPhotos    
  - Components => Gallery.js   

5. Image Placeholder + blurDataURL   
  - https://youtu.be/noR4Ben87Sw?si=gk1nN-RU0QNh6vsI   

6. Infinite Scroll Pagination ( 1st Way )
  - Pagination
  - Load More
  - Infinite Scroll

7. Optimized for blurDataURL.

8. Infinite Scroll Pagination ( 2nd Way )

9. Deploy Vercel   

📚 Materials/References:  
  - https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API
