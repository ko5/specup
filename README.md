문제 1
장고를 설치해서 해봤지만, history가 만들어진 datetime는 할 수 있었지만 
다른 부분은 하지 못하였습니다. 



문제 2
SELECT c.type, sum(u.profit)
From Content as c, UserContent as u
WHERE c.id = u.content_id
GROUP By c.type;
