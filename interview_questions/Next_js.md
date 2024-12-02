1. What is Next JS?

- Next JS is an open-source web development React-based framework created by Vercel, which is 
 famous for its unique features such as Server-side rendering and enhanced SEO.


2.  What are the benefits of using Next JS?
Next.js is a popular React framework that brings several benefits to web development

- Enhanced SEO

- Faster page loads 

- Better user experience

- Better performance

- Easier deployment

- Easier maintenance

3. What is getStaticProps?

- getStaticProps is a function in Next.js that is used to fetch data from a data source and 
pass it to a component as props. And User can make a request to the server to get the data.

-  This provides faster page loads, improves SEO


4. What is getServerSideProps?

- A function used for server-side rendering to fetch data on each request. 


5. What is the Link component in Next.js?

- The Link component is used to create links to other pages in your Next.js application.


Example:

// pages/about.js
import Link from 'next/link';

function AboutPage() {
  return (
    <div>
      <h1>About Us</h1>
      <p>This is the about page of our application.</p>
      <Link href="/">
        <a>Go back to Home Page</a>
      </Link>
    </div>
  );
}

export default AboutPage;
