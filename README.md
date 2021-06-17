# DynamicPaginationAspDotNetCore
Dynamic for List&lt;T> (Generic)

<b>
  Easy pagination for asp.net core mvc or webApi.
</b>
<p>
  First please give me a star. 💖
 </p>
 <br/>
 <br/>
 
 <strong>
  Using instructions : 
  </strong>
  <p>
var list = PagedList<T>.ToPagedList(List items, Page Number, Page Size)
  <br/>
  return View(list);
  
  
  // List props includes :
  <h3>
    int TotalPage
      </h3>
  <h3>
    int TotalCount
    </h3>
  <h3>
    int PageSize
  </h3>
  <h3>
    int CurrentPage
    </h3>
  <h3>
    bool HasNext
    </h3>
  
  <h3>
    bool HasPrevious
    </h3>

  </p>
