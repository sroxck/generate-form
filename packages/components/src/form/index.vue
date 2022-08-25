<script  lang="ts">
import { defineComponent, h, PropType, ref } from "vue-demi";
import type { Schema } from "./useForm";
import { ElButton } from "element-plus";
export default defineComponent({
  props: {
    schema: {
      type: Object as PropType<Schema>,
      required: true,
    },
  },
  setup(prop, ctx) {
    console.log(prop.schema,);
    
    return ()=>{
      return h('div','33')
    }
    
  },
});

</script>