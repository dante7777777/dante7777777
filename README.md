components/RPCList/index.jsist({ chain, lang }) 
  return (	  return (
    <div className="shadow dark:bg-[#0D0D0D] bg-white p-8 rounded-[10px] flex flex-col gap-3 overflow-hidden col-span-full relative overflow-x-auto">	    <div className="shadow dark:bg-[#0D0D0D] bg-white p-8 rounded-[10px] flex flex-col gap-3 overflow-hidden col-span-full relative overflow-x-auto">

      <table className="m-0 border-collapse whitespace-nowrap dark:text-[#B3B3B3] text-black">	      <table className="m-0 border-collapse whitespace-nowrap dark:text-[#B3B3B3] text-black">
        <caption className="relative w-full px-3 py-1 text-base font-medium border border-b-0">	        <caption className="relative w-full px-3 py-1 text-base font-medium border border-b-0">
@@ -120,22 +119,22 @@ export default function RPCList({ chain, lang }) {


        <tbody>	        <tbody>
          {rpcData.map((item, index) => {	          {rpcData.map((item, index) => {
            let className = 'bg-inherit';	            let className = "bg-inherit";


            }	            }


            return (	            return (
              <Row	              <Row
                values={item}	                values={item}
                chain={chain}	                chain={chain}i love github haha
do u know me ??
haha

