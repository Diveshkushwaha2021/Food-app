//	const heading = React.createElement("h1", { id: "heading" }, "hello world");
// JSX is a syntax
// react is an object


const StyleCard = {
// 	backgroundColor: "#ee3c4d",
// 	color: "#fafafa"
// }

<!-- <div className="res-card" style={StyleCard}><h2>hello</h2></div> -->

// apisData?.data; this we can can say "Optional chaning" 

//and this we can say "Destructring" const { cloudinaryImageId, name, cuisines, avgRating, deliveryTime } = apisData?.data;

//Map in js to fetch all restaurant cards	
//{
//	apis.map((restaurant) => (<Rescards apisData={restaurant} />))
//}
	// {react variable, function start with "set"}
	// here if i want to update the value of react variable we can't do it directly
	// So setlistofrestaurant update the state of variable
	//like: if i want to make array list empty then
	// Setlistofrestaurant([]);
	when ever a state variable update recat re-render the components
//Virtual Dom : it is an object representation of js or actual DOM.

//chapter 6
// useState variable
// whenever state variables update, react trigger reconciliation cycle(re-renders the Components)
//this concept of updating two dom in react fiber or reconciliation make it faster.

//OPtional chaining
//son?.data?.success?.cards[4]?.gridWidget?.gridElements?.infoWithStyle?.restaurants

//map, filter and reduce
