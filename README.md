# resize-any-website-you-want
this change css of any web. Of course, this only happen in your display (only in chorme or firefox)

step 1: go to chorme extensions
step 2: install extension: Stylus (icon S - green - update last 1/4/2026)
step 3: back your web you want to change css 
step 4: open Stylus 
step 5: Click exactly their url / click Manage and find it
step 6: change https://knowt.com/study/flashcards/41fd6820-2b76-45ae-bc28-6d39223915eb1/learn or something like that to https://knowt.com/study/flashcards/    (doing with same web have same start url)
step 7: paste this:

@-moz-document url-prefix("https://knowt.com/study/flashcards/") {
div.breakpoints-module__zbexiG__smDownDisplayNone {
    padding-top: 5px !important; /* Ghi đè 40px bằng 5px */
}
    div.breakpoints-module__zbexiG__mdDownColumnReverse{
        margin: 30px 0px 0px 0px!important;
    }
    
   /* 2. Tối thiểu hóa phần ngăn cách chứa chữ "Select the matching term" */
span.bold {
    margin-bottom: 2px !important; /* Ghi đè 1rem */
    font-size: 0.8rem !important;  /* Thu nhỏ chữ hướng dẫn lại để tiết kiệm diện tích */
    display: block !important;
}
    div.studyPage-module__2Yqjuq__flashcardCard{
        font-size: 5.7rem;
        padding: 30px 10px 10px 10px !important;
    }    
    p{
        font-size: 3.7rem 
    }
div.breakpoints-module__zbexiG__mdDownColumnReverse div.ProseMirror {
    margin-left: 90px !important;
}
div.studyNavbar-module__ci9FBa__container {
    height: 60px !important; /* Ép chiều cao mỏng lại */
    padding-top: 0px !important;
    padding-bottom: 0px !important;
    gap: 0.5rem !important; /* Thu hẹp khoảng cách giữa các nút */
    overflow: hidden !important; /* Ẩn đi những phần tử thừa bị tràn */
}
    div.studyPage-module__2Yqjuq__container{
        height: calc(100vh - var(--90vh)) !important;
    }
    div.knowt-lbl9ok{
         padding: 18px !important;
    }
    
    /* 3. Phóng to cỡ chữ phần trả lời thêm 50% */
.flashcardWithAnswerInput-module__IzbJIa__optionTemplateColumn {
    gap: 1rem !important; /* Thu hẹp một chút khoảng trống giữa các đáp án nếu cần */
}
}



<img width="1888" height="861" alt="Screenshot 2026-04-01 100309" src="https://github.com/user-attachments/assets/db2b0774-1f78-4c56-8690-4ff85e36c788" />


