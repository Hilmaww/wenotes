<template>
    <div class="listNotes">
        <ul>
            <li v-for="row in notes">
                {{row.title}}
            </li>
        </ul>
    </div>
</template>

<script type="text/javascript">

    exports : default{
        name= 'listNotes',
        data : function(){
            return{
                notes : [
                    {title : 'wegodev',
                      description : 'ini isi wegodev'}
                ]

            }
        }
    }

</script>