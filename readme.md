# Book App

This is a basic react app with CRUD operation features. Although it's only performing crud operations, it is built combining with a lots of React's core features. For managing state, Context API is used while keeping the idea of 'state lifting up' pattern along using with props. useCallback hook was used to prevent infinite re-rendering as the useEffect used a function as it's dependency array. This application was very carefully designed by separating application state and component states. Props types were checked using React's prop validation. JSON server was used to persist the data across the application. Rest-client is used for api documentation. Overall this Book CRUD application covers many of Reacts core feature. 

# How to run

    
        Frontend: npm run dev
        Server: npm run server
    