<script>
  import {
    Collapse,
    Navbar,
    NavbarToggler,
    NavbarBrand,
    Nav,
    NavItem,
    NavLink,
    Dropdown,
    DropdownToggle,
    DropdownMenu,
    DropdownItem
  } from 'sveltestrap';

  import { url } from '@roxi/routify'
  
  let isOpen = false;

  function handleUpdate(event) {
    isOpen = event.detail.isOpen;
  }
</script>

<Navbar color="light" light expand="md">
  <NavbarBrand href="/">Logo</NavbarBrand>
  <NavbarToggler on:click={() => (isOpen = !isOpen)} />
  <Collapse {isOpen} navbar expand="md">
    <Nav class="mx-auto" color="dark" navbar>
      <NavItem>
       <NavLink href='/'>Beranda</NavLink>
      </NavItem>
      <NavItem>
        <NavLink href={$url('../routes/404/errorPage')}>Persyaratan dan ketentuan</NavLink>
      </NavItem>
      <NavItem>
        <NavLink href={$url('../routes/404/errorPage')}>tentang kami</NavLink>
      </NavItem>
    </Nav>
    <Nav class="ms-auto" navbar>
      <NavItem>
       <NavLink href="#components/">
        <svg style="width:24px;height:24px" viewBox="0 0 24 24">
    <path fill="currentColor" d="M19,3H5C3.89,3 3,3.89 3,5V9H5V5H19V19H5V15H3V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5C21,3.89 20.1,3 19,3M10.08,15.58L11.5,17L16.5,12L11.5,7L10.08,8.41L12.67,11H3V13H12.67L10.08,15.58Z" />
</svg> Login / Register
       </NavLink>
      </NavItem>
    </Nav>
  </Collapse>
</Navbar>