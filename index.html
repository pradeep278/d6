				'".$rowData['category_id']."',
                '".$rowData['request_id']."'
                )";
        mysqli_query($this->con,$sql);
        return $this->con->insert_id;
    }
    
```

#### Step 10:
   On inserting the JSON response into master and child tables, the status and Request date will be updated for that record in the Request table by function **updateToneAnalyzerTextData($id)** in controller.


#### Step 11:
   To get the Master list function **getALLMasterDataFromMySQL** will be called from controller.
   
#### Step 12:
   To view the Master list function **showallMasterListView()** will be called from controller to View.
   
**_Code:_**

```
   function showallMasterListView($data_arr){
        $smarty = new Smarty();
        $smarty->assign('base_path',$GLOBALS['base_path']);
		$smarty->assign('cursor',$data_arr);
	    $smarty->display(''.$GLOBALS['root_path'].'/Views/BluemixToneAnalyzer/allmasterList.tpl');
    }
    
``` 

#### Step 13:
   To view the Child data based on the master id, function **getChildDataFromMySQL($post_data)** will be called from controller.
   Function **getAllChildDataFromMySQL($post_data)** will get the reocrds based on the master id using MySql query. Function **showDetailListView($bluemix_list_vo)** will be called in view. 
   
**_Controller page Code:_**

```
public function getChildDataFromMySQL($post_data){
        $bluemix_action = BluemixToneAnalyzerAction::getInstance();            
        $bluemix_list_vo = $bluemix_action->getAllChildDataFromMySQL($post_data);
		$bluemix_view = BluemixToneAnalyzerView::getInstance();            
    	$bluemix_view->showDetailListView($bluemix_list_vo);
	}
```
**_View page Code:_**

```
function showDetailListView($data_arr){
        $smarty = new Smarty();
        $smarty->assign('base_path',$GLOBALS['base_path']);
		$smarty->assign('cursor',$data_arr);
	    $smarty->display(''.$GLOBALS['root_path'].'/Views/BluemixToneAnalyzer/detailList.tpl');
    }
```
