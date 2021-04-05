<template>
    <div class="container-fluid container-register d-flex flex-column justify-content-center">
        <div class="row">
            <div class="col-md-4 mx-auto">
                <form>
                <div class="form-group">
                    <label for="exampleInputUsername">E-mail</label>
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">Username</label>
                    <input type="text" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">Tahun Masuk</label>
                    <input type="text" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">Tahun Lulus</label>
                    <input type="text" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">Jurusan</label>
                    <input type="text" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">Tanggal lahir</label>
                    <input type="text" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">Alamat</label>
                    <input type="date" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">No telp</label>
                    <input type="text" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputEmail">Pekerjaan</label>
                    <input type="text" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-group">
                    <label for="exampleInputPassword1">Password</label>
                    <input type="password" class="form-control" id="exampleInputPassword1">
                </div>    
                <button type="submit" class="btn btn-primary">Register</button>
                </form>
            </div>
        </div>
    </div>
</template>

<style>
.container-register{
    height:170vh;
}
</style>