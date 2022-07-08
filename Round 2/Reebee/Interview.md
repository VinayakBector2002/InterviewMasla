class Tree(
  val value: Int,
  val left: Tree?,
  val right: Tree?
)

// recursion for this 
// Dealing to for loop approach
// RECURSION
//		BASE CASE = NULL PTR ! BECAUSE TREE ENDS (LEAF NODE)
// 		RECUR CASE
//			GENERAL STRATEGY FOR SOLVING
// 		
//fun isTreeIdentical(t1: Tree?, t2: Tree?): Boolean {
		// COMPARE THE THE VALUES OF T1 AND T2 AND THE FOLLOWING CALL
  	// CALL isTreeIdentical(LEFT T1, LEFT T2) "AND BOOLEAN OPERATOR" isTreeIdentical(RIGHT T1, RIGHT T2)
  	// TRAVERSE THRU EACH OF THE VALUES IN THE GIVEN TREES (CORRESPONDING VALUES)
  	// SINCE, WE ARE USING THE AND OPERATOR EVEN IF ONE OF THE OPERATIONS RETURN FASLE THEN THE WHOLE FUNCTION WILL RETURN FALSE
  	// TRUE, OTHERWISE 
//}

// SWIFT??
// Yeah you can write in swift if you want :)
func isTreeIdentical(t1: Tree?, t2: Tree?) -> Bool {
  // nil collasing operator 
  // Condition 
  //
  if ((t1 == nil) and (t2 == nil)){ // <- necessary
    return true;
  } else if (t1 == nil) or (t2 == nil){
    return false;
  }
  // (First Condition is TRUE)
  return (t1?.value == t2?.value) and (isTreeIdentical(t1?.left, t2?.left)) and (isTreeIdentical(t1?.right , t2?.right))
}
// You may have to type out your thoughts, you are breaking up.


let result = isTreeIdentical(nil, nil)

// Can you please type : (

// This position is fully remote, and we have flexible work hours. We have core hours of 10am -3pm EST.
// The compensation for the position, since it is your first term, we will pay you as if it is actually your second work term:
// $22.05 / hr
// That's about it for the important info! What questions do you have for us?

// JUST ONE QUESTION FOR BOTH OF YOU : 
//		Ques. 

// Why do we work for reebee?
// Xavier: small team means that I have a lot of control as to what happens - I can give my feedback, and see it implemented immediately. 
// Being in a small team means I get to know my coworkers better, and form closer relationships.
// It also means that we can move quickly when change is required, so whenever we need to overcome a new challenge,
// we can work on it immediately and collaborate closely to get it done quickly.
// You get what you put in. If you take initiative, you can accomplish whatever your goal is.

// Jaewon: as a small team we have a lot of opportunities. At the moment, reebee is having a lot of changes in the development process,
// which gave me the opportunity to not only work as a team lead but also as a scrum master, and also as a tech lead. 
// This means there is a lot of opporunities as long as you have the enthusiasm to work on different things.
// There is also the culture: Dream, Build, Together. There is a high level of trust between coworkers at reebee, and we work to achieve our goals together.
// WOW THANK YOU ! FOR YOUR ANSWERS IT HELPS ME GET A GREAT INSIGHT ABOUT THE COMPANY ESPECIALLY THE CULTURE
// The fact that you mentioned about the opportunity speaks volumes about the compnay's leadership and enviornment 
// I would love you work at a place like Reebee under the guidance of such lovely seniors <3 
// YES!! 
// This is one of the chillest interviews that I ever had 
// 		Despite all the technical difficulties
//		

// I am glad that you enjuoyed the interview, that is very important to us :)
// Do you have any other questions?

// Sorry Can you Type :(

//  THANK YOU VERY MUCH <3
// Great to talking with you.

// BYE HAVE A GOOD ONE THANK YOU CHEERS


