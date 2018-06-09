<template>
  <Page style="background-color:red">

    <StackLayout>
      <TextField :text="textFieldValue" hint="Username" style="color:white;padding:10px" />
      <Button class="btn btn-primary" @tap="$router.push('/hello')">Hello World</Button>
    </StackLayout>

  </Page>
</template>
