<?php

namespace AppModelBundle\Entity;

use Doctrine\ORM\Mapping as ORM;

/**
 * RelUserFolder
 */
class RelUserFolder
{
    /**
     * @var integer
     */
    private $id;

    /**
     * @var boolean
     */
    private $isOwner;

    /**
     * @var \AppModelBundle\Entity\User
     */
    private $user;

    /**
     * @var \AppModelBundle\Entity\Folder
     */
    private $folder;


    /**
     * Get id
     *
     * @return integer 
     */
    public function getId()
    {
        return $this->id;
    }

    /**
     * Set isOwner
     *
     * @param boolean $isOwner
     * @return RelUserFolder
     */
    public function setIsOwner($isOwner)
    {
        $this->isOwner = $isOwner;

        return $this;
    }

    /**
     * Get isOwner
     *
     * @return boolean 
     */
    public function getIsOwner()
    {
        return $this->isOwner;
    }

    /**
     * Set user
     *
     * @param \AppModelBundle\Entity\User $user
     * @return RelUserFolder
     */
    public function setUser(\AppModelBundle\Entity\User $user = null)
    {
        $this->user = $user;

        return $this;
    }

    /**
     * Get user
     *
     * @return \AppModelBundle\Entity\User 
     */
    public function getUser()
    {
        return $this->user;
    }

    /**
     * Set folder
     *
     * @param \AppModelBundle\Entity\Folder $folder
     * @return RelUserFolder
     */
    public function setFolder(\AppModelBundle\Entity\Folder $folder = null)
    {
        $this->folder = $folder;

        return $this;
    }

    /**
     * Get folder
     *
     * @return \AppModelBundle\Entity\Folder 
     */
    public function getFolder()
    {
        return $this->folder;
    }
}
