# cautious-train

nth_element([H|_],1,H):- !.
nth_element([_|T],N,H):-N1 is N-1, nth_element(T,N1,H).
