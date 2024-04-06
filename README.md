# Project Description
This project provides comprehensive guidelines on how to install and use Django. It includes creating an application, preparing models, using faker to load fake data, enhancing Django admin functionality, and creating a `requirements.txt` file.

# Authors
- Samantha Anne P. Quizon
- Ria Joy Brizo
<<<<<<< HEAD



{% if is paginated %}

<div class="card-footer px-0 border-0 content—between mt-3"> “mb-4"> 
 <nav aria-label="Topics pagination” class= 

   <ul class="pagination"> 
  {% if page _obj.number > 1 %} 
  <li class="page-item"> 
  <a class="page-1ink" href="?page=1">First</a> 
  </li> 
  {% else %} 
  <li class="page-item disabled"> 
    <span class="page-link">First</span> 
</li> 
{% endif %} (% if page_obj.has_previous %} 
<li class="page-item"> 
  <a class="page-link" href="?page={{ page_obj.previous_page_number }}">Prev</a>
</li> 
{% else %} 
<li class="page-item disabled”> 
  <span class="page-link">Prev</span> 
</li> 
 {% endif %} {% for page_num in paginator.page_range %} {% if page_obj.number == page_num %} 
 
<li class="page-item active"> 
  <span class="page-link"> 
    {{ page_num }} 
    <span class="sr-only">(current)</span> 
  </span> 
</li> 
{% elif page_num > page_obj.number|add:'-3' and page_num < page_obj.number|add:'3' %} 
<li class="page-item"> 
  <a class="page-link" href="?page={{ page_num }}">{{ page_num }}</a> 
  </li> {% endif %} {% endfor %} {% if page_obj.has_next %} 
  <li class="page—item"> 
   <a class="page-link" href="?page={{ page_obj.next_page_ number }}">Next</a>
  </li> {% else %} 
   <li class="page-item disabled"> 
    <span class="page-link”>Next</span> 
   </li> 
   {% endif %} {% if page_obj.number != paginator.num_pages %} 
   <li class="page-item"> 
     <a class="page-link" href="?page={{ paginator.num_pages }}">Last</a> 
     </li> 
     {% else %} 
     <li class=“page-item disabled”> 
        <span class="page-link">Last</span> 
     </li>
    {% endif %}
    </ul>
  </nav>
  <div class="fw-normal small mt-4 mt-lg-0">Showing <b>{{object_list.count}}</b> out of 
<b>{{paginator.count}}</b> entries</div> 
</div> 
{% endif %} 
=======
>>>>>>> 1b3e9849dd92df8dee58c142e7915dbfb7392d0b
