# unnest_token.subtitles works as expected

    Code
      unnest_tokens(tbl = s)
    Output
      # A tibble: 36 x 5
         ID    Timecode_in Timecode_out Text_content test 
         <chr> <time>      <time>       <chr>        <chr>
       1 1     00'01.0010" 00'01.6250"  never        Test 
       2 1     00'01.6260" 00'02.2500"  drink        Test 
       3 1     00'02.2510" 00'03.0000"  liquid       Test 
       4 1     00'03.0010" 00'04.0000"  nitrogen     Test 
       5 2     00'05.0010" 00'05.2162"  it           Test 
       6 2     00'05.2172" 00'05.6486"  will         Test 
       7 2     00'05.6496" 00'06.6216"  perforate    Test 
       8 2     00'06.6226" 00'07.0541"  your         Test 
       9 2     00'07.0551" 00'07.8108"  stomach      Test 
      10 2     00'07.8118" 00'08.1351"  you          Test 
      # i 26 more rows

