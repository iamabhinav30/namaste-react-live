## UI Layer --> JSX --babel-> JS Objects (Virtual DOM) --> Helpful for Reconsilation (between render check diff between old VDOM and new VDOM and diff will keep in sync with actual DOM)
## Data Layer rendered UI --> we use state and props to handle the data


<!--
TESTING USING JEST & CONFIGURATION
/**
 * Different types of testing
 *  - Manual Testing
 *  - Automated testing (code test the code)
 *      - Selenium Testing
 * 
 *  - E2E Testing (testing a full flow) - COvers entire user Journey
 *      - Cypress  
 * 
 *  - Unit Testing (Testing small units)
 * 
 *  - Integration Testing (Testing Integration between the components)
 * 
 * Intall REact Testing library
 *  npm i --save-dev @testing-library/react
 * 
 * Install Jest
 *  npm i -D jest
 *  
 * Configure Jest
 *  npx jest --init
 *  
 * Install jest-environment-jsdom
 *  npm i -D jest-environment-jsdom
 * 
 * Create my first test
 * 
 * Configure Bable
 * npm install --save-dev babel-jest @babel/core @babel/preset-env
 * create babel.config.js or .bablerc
 * 
 Wrote expect sum test
 wrote .gitignore my coverage
 * json and js object
 * 
 * configure babel/preset-react
 */ -->

<!-- we get the readible stream form API we convert it to JSON -->

<!-- 
    REDUX  use only for Large Applications
    Redux Toolkit

useCOntext is because to avoid prop drilling

-->

<!-- state and props
    local variable is the STATE
    PROP is value passed from one component to another components
    (prop are local state from body)
    Root comp APP
 -->
Flux
NgRx
Context
 <!-- 
     AppLayout
        (user)
            - <Body user ={user} />
                - RestaurantCard user={user}
                    - <h4>{user}</h4>
    PROP Drilling

    Lifting the State up
    
    (when instamart will take care of state of below section) 

       {/** Outlet will be filled by the children configurations
Accouridng to ourlet all the children go in  */}

      /**
     * Header
     *      - Logo
     *      - Nav Items(right side)
     *      - Cart
     * Body
     *      - Search bar[](C:/)
     *      - Restaurent List
     *              - Restaurant Card
     *                      - Image, Name, Rating, Cusines
     * Footer
     *      - Links
     *      - copyright


     
 class About extends React.Component {
     constructor(props){
         super(props);
          parent constructor 1
        
     }
     componentDidMount(){
         console.log('2nd call');
          Best place to make API call
          parent componentDidMOunt6
     }
     render() {
          parent render 2
         return (
             <div>
                 <h1>About Class us page</h1>
                 <p>
                     {" "}
                     This is the Namaste React Live Course
                 </p>
                 <ProfileC name={'Abhinav'}/>
                 <Outlet />
             </div>
         );
     }
 }


     */

 -->