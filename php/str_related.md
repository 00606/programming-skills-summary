###�ַ������

####��������ַ���
	<?php
	function randstr($len) { 
        $c = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
        $ret = "";
        for($i=0; $i<$len; $i++) { 
            $ret.= $c[rand()%strlen($c)]; 
        }
        return $ret; 
	}
	?>